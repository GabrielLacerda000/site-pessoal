<script setup>
import Anchor from '../components/Anchor.vue'
</script>

<template>
    <nav class="text-sky-600 text-lg mx-3">
        <ul class="grid grid-cols-5 gap-1 font-semibold">
          <li class="text-center">
             <Anchor text="home"/>
          </li>

          <li class="text-center">
            <Anchor text="about"/>
          </li>

          <li class="text-center">
            <Anchor text="portfolio"/>
          </li>

          <li class="text-center">
            <Anchor text="contact"/>
          </li>

          <li class="text-center">
            <Anchor text="services"/>
          </li>
        </ul>
    </nav>
</template>