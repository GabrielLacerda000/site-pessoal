<script setup>
    defineProps({
        text: String
    })
</script>

<template>
    <a href="#" class="block p-1 hover:text-sky-300 transition duration-300 ease-in-out">{{ text }}</a>
</template>