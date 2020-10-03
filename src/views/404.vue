<template>
  <main class="bg-teal-800">
    <div class="gradient text-white min-h-screen flex items-center">
      <div class="container mx-auto p-4 flex flex-wrap items-center">
        <div class="w-full md:w-5/12 text-center p-4">
          <img src="https://themichailov.com/img/not-found.svg" alt="Not Found" />
        </div>
        <div class="w-full md:w-7/12 text-center md:text-left p-4">
          <div class="text-6xl font-medium">404</div>
          <div class="text-xl md:text-3xl font-medium mb-4">
            Oops. This page has gone missing.
          </div>
          <div class="text-lg mb-8">
            You may have mistyped the address or the page may have moved.
          </div>
          <router-link
              to="/"
              class="p-2 text-gray-700 leading-5 hover:text-white bg-blue-300 hover:bg-blue-500 rounded">
            Home
          </router-link>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "404"
}
</script>

<style scoped>

</style>