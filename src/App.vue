<script setup>
import RemaininLives from './components/remaininLives.vue';
</script>

<template>
    <div class="bg-image min-h-screen min-w-full flex flex-col">
      <div class="container mx-auto flex-grow flex flex-col justify-around">
       <div class="">
        <p class="text-2xl text-center text-white mb-0 gaming-text">SCORE </p>
        <p class="text-6xl text-center text-white my-0">2 0 0 0</p>
       </div>
        <p class="text-xl text-center text-white mb-0 gaming-text">VERBLEIBENDE LEBEN</p>
        <div class="flex justify-around gap-5 md:w-10/12 sm:w-10/12 sm:mx-auto w-8/12 mx-auto overflow-hidden">
      <RemaininLives />
        </div>

        <div class="">
          <p class="text-xl text-center text-white mt-1 gaming-text">ZEIT</p>
        <p class="text-6xl text-center text-white mt-1 mb-0">0 0 : 3 0 : 0 0</p>
        </div>
        <img class="w-1/12 mx-auto" src="./assets/SVG/J7Cxvo.svg" alt="" />
       
      </div>
    </div>
</template>

<style>
.bg-image {
  background-image: url("./assets/bg.svg");
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
}

</style>
