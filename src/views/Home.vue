<template>
  <div class="home">
    <div class="container mx-auto px-6 py-16">
      <div class="md:flex items-center">
        <div class="w-full md:w-1/2">
          <div class="max-w-lg">
            <h1 class="text-gray-800 text-2xl font-semibold uppercase md:text-3xl">Best Place To Choose Your Clothes</h1>
            <p class="mt-2 text-gray-600">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Porro beatae error laborum ab amet sunt recusandae? Reiciendis natus perspiciatis optio.</p>
            <button class="mt-4 px-3 py-2 bg-indigo-600 text-white text-sm uppercase font-medium rounded hover:bg-indigo-500 focus:outline-none focus:bg-indigo-500">Shop Now</button>
          </div>
        </div>

        <div class="flex items-center justify-center w-full mt-6 md:mt-0 md:w-1/2">
          <img class="max-w-2xl w-full h-full" src="../assets/img/catalogue.svg" alt="">
        </div>
      </div>
    </div>
    <Team />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src

import Team from "@/components/Team";
import Footer from "@/components/Footer";
export default {
  name: 'Home',
  components: {
    Footer,
    Team
  }
}
</script>
