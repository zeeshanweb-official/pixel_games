<script setup>
import ImageComponent from './imageComponent.vue';
const remaingLives = 2
const totalLives=5
</script>
<template>
    <ImageComponent v-for="(item,index) in totalLives" :key="index" :color="index<=remaingLives?'green':'red'" />
    <!-- <img class="md:w-1/6 sm:w-2/12 w-1/12" src="@/assets/SVG/Asset 1.svg" alt="" />
    <img class="md:w-1/6 sm:w-2/12 w-1/12" src="@/assets/SVG/Asset 4.svg" alt="" />
    <img class="md:w-1/6 sm:w-2/12 w-1/12" src="@/assets/SVG/Asset 6.svg" alt="" />
    <img class="md:w-1/6 sm:w-2/12 w-1/12" src="@/assets/SVG/Asset 5.svg" alt="" />
    <img class="md:w-1/6 sm:w-2/12 w-1/12" src="@/assets/SVG/Asset 8.svg" alt="" /> -->
</template>
<style></style>