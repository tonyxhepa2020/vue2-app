<template>
  <nav class="bg-white shadow">
    <div class="container mx-auto px-6 py-3">
      <div class="flex flex-col md:flex-row md:justify-between md:items-center">
        <div class="flex justify-between items-center">
          <div class="flex items-center">
            <a class="text-gray-800 text-xl font-bold md:text-2xl hover:text-gray-700" href="#">Brand</a>
            <!-- Search input on desktop screen -->
            <div class="mx-10 hidden md:block">
              <input type="text" class="w-32 lg:w-64 px-4 py-3 leading-tight text-sm text-gray-700 bg-gray-100 rounded-md placeholder-gray-500 border border-transparent focus:outline-none focus:bg-white focus:shadow-outline focus:border-blue-400" placeholder="Search" aria-label="Search">
            </div>
          </div>

          <!-- Mobile menu button -->
          <div class="flex md:hidden">
            <button @click="isMobileOpen = !isMobileOpen" type="button" class="text-gray-500 hover:text-gray-600 focus:outline-none focus:text-gray-600" aria-label="toggle menu">
              <svg viewBox="0 0 24 24" class="h-6 w-6 fill-current">
                <path fill-rule="evenodd" d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"></path>
              </svg>
            </button>
          </div>
        </div>

        <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
        <div :class="{ 'block': isMobileOpen, 'hidden': !isMobileOpen}" class="md:flex items-center">
          <div class="flex flex-col mt-2 md:flex-row md:mt-0 md:mx-1">
               <router-link
                to="/"
                class="my-1 text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline md:mx-4 md:my-0">
                 Home
               </router-link>
            <router-link
                to="/about"
                class="my-1 text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline md:mx-4 md:my-0">
              About
            </router-link>
            <router-link
                to="/404"
                class="my-1 text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline md:mx-4 md:my-0">
              404
            </router-link>
          </div>

          <div class="flex items-center py-2 -mx-1 md:mx-0">
            <router-link
                to="/login"
                class="block w-1/2 px-3 py-2 mx-1 rounded text-center text-sm bg-gray-500 font-medium text-white leading-5 hover:bg-blue-600 md:mx-2 md:w-auto">
              Login
            </router-link>
          </div>
          <!-- Search input on mobile screen -->
          <div class="mt-3 md:hidden">
            <input type="text" class="w-full px-4 py-3 leading-tight text-sm text-gray-700 bg-gray-100 rounded-md placeholder-gray-500 focus:outline-none focus:bg-white focus:shadow-outline" placeholder="Search" aria-label="Search">
          </div>
        </div>
      </div>

      <div class="mt-3 py-3 -mx-3 overflow-y-auto whitespace-no-wrap scroll-hidden">
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">News</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">Articles</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">Videos</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">Tricks</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">PHP</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">Laravel</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">Vue</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">React</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">Tailwindcss</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">Meraki UI</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">CPP</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">JavaScript</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">Ruby</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">Mysql</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">Pest</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">PHPUnit</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">Netlify</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">VS Code</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">PHPStorm</a>
        <a class="text-sm text-gray-700 leading-5 hover:text-blue-600 hover:underline mx-4 md:my-0" href="#">Sublime</a>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
name: "Nabar",
  data() {
  return {
    isMobileOpen: false
  }
  }
}
</script>

<style scoped>

</style>