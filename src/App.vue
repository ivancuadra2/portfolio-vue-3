<script setup lang="ts">
// import HelloWorld from './components/HelloWorld.vue'
import Navigation from './components/Navigation.vue'
import BannerHeader from './components/BannerHeader.vue'
// import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
</script>

<template>
  <div class="">
    <Navigation />
    <BannerHeader />
    <font-awesome-icon class="" :icon="['fab-xl', 'react']" />
    <!-- <div class="p-6 max-w-sm mx-auto bg-white rounded-xl shadow-md flex items-center space-x-4">
      <div class="flex-shrink-0">
        <img class="h-20 w-20" src="./assets/personalLogo.png" alt="Ivan Logo">
      </div>
      <div>
        <div class="text-xl font-medium text-black">Ivan Cuadrado</div>
        <p class="text-gray-500">Senior Developer</p>
      </div>
    </div>
    
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a> -->
  </div>
  <!-- <HelloWorld msg="Vite + Vue" /> -->
</template>

<style scoped>

</style>
