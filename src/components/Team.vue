<template>
  <main>
    <section class="bg-gray-100 lg:py-12 lg:flex lg:justify-center">
      <div class="bg-white lg:mx-8 lg:flex lg:max-w-5xl lg:shadow-lg lg:rounded-lg">
        <div class="lg:w-1/2">
          <div class="h-64 bg-cover lg:rounded-lg lg:h-full" style="background-image:url('https://images.unsplash.com/photo-1497493292307-31c376b6e479?ixlib=rb-1.2.1&auto=format&fit=crop&w=1351&q=80')"></div>
        </div>

        <div class="py-12 px-6 max-w-xl lg:max-w-5xl lg:w-1/2">
          <h2 class="text-2xl text-gray-800 font-bold md:text-3xl">Build Your New <span class="text-indigo-600">Idea</span></h2>
          <p class="mt-4 text-gray-600">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quidem modi reprehenderit vitae exercitationem aliquid dolores ullam temporibus enim expedita aperiam mollitia iure consectetur dicta tenetur, porro consequuntur saepe accusantium consequatur.</p>

          <div class="mt-8">
            <a href="#" class="bg-gray-900 text-gray-100 px-5 py-3 font-semibold rounded hover:bg-gray-800">Start Now</a>
          </div>
        </div>
      </div>
    </section>
    <section class="bg-white container mx-auto p-6">
      <h2 class="text-gray-800 font-medium capitalize text-xl md:text-2xl">Our Team</h2>

      <div class="flex items-center justify-center">
        <div class="grid gap-8 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 mt-8">
          <div class="max-w-xs w-full text-center">
            <img class="h-48 w-full object-cover object-center mx-auto rounded-lg" src="https://images.unsplash.com/photo-1493863641943-9b68992a8d07?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=739&q=80" alt="avatar"/>

            <div class="mt-2">
              <h3 class="text-lg font-medium text-gray-700">Ahmed Omer</h3>
              <span class="mt-1 font-medium text-gray-600">CEO</span>
            </div>
          </div>

          <div class="max-w-xs w-full text-center">
            <img class="h-48 w-full object-cover object-center mx-auto rounded-lg" src="https://images.unsplash.com/photo-1516756587022-7891ad56a8cd?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=334&q=80" alt="avatar"/>

            <div class="mt-2">
              <h3 class="text-lg font-medium text-gray-700">Jane Doe</h3>
              <span class="mt-1 font-medium text-gray-600">Co-founder</span>
            </div>
          </div>

          <div class="max-w-xs w-full text-center">
            <img class="h-48 w-full object-cover object-center mx-auto rounded-lg" src="https://images.unsplash.com/photo-1492562080023-ab3db95bfbce?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=731&q=80" alt="avatar"/>

            <div class="mt-2">
              <h3 class="text-lg font-medium text-gray-700">Steve Ben</h3>
              <span class="mt-1 font-medium text-gray-600">UI/UX</span>
            </div>
          </div>

          <div class="max-w-xs w-full text-center">
            <img class="h-48 w-full object-cover object-center mx-auto rounded-lg" src="https://images.unsplash.com/photo-1517841905240-472988babdf9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=334&q=80" alt="avatar"/>

            <div class="mt-2">
              <h3 class="text-lg font-medium text-gray-700">Patterson Johnson</h3>
              <span class="mt-1 font-medium text-gray-600">Software Engineer</span>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {
name: "Team"
}
</script>

<style scoped>

</style>