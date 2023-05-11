<script setup>
import HomeHeader from '../components/Home/Header/HomeHeader.vue';
import HomeFooter from '../components/Home/Footer/HomeFooter.vue';
</script>

<template>
  <div class="flex flex-col h-screen w-full m-0 p-0 bg-white">
    <header>
      <HomeHeader />
    </header>
    <main class="flex-grow">
      <router-view />
    </main>
    <footer>
      <HomeFooter />
    </footer>
  </div>
</template>
