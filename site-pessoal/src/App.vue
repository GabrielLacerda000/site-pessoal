<script setup>
import Navbar from './components/Navbar.vue'
import Content from './components/Content.vue'
import { BiFacebook } from "oh-vue-icons/icons"
</script>

<template>
  <main class="grid grid-rows-[50px_1fr_50px] min-w-screen min-h-screen">
    
    <header class="flex justify-between w-full p-3">
      <p class="bg-clip-text text-transparent bg-gradient-to-r from-sky-600 to-sky-800 text-3xl font-semibold mx-3">Jacob</p>
      <Navbar />  
    </header>

    <section class="grid grid-cols-2 w-auto mx-8 gap-2 place-content-center">
      <Content />
      <div class="">
          <img src="../public/img/wireframe.svg" alt="pc" class="h-96 w-full bg-center bg-cover rounded-md drop-shadow-2xl">
      </div>
    </section>
    
    <footer class="">
      
    </footer>
  </main>
</template> 