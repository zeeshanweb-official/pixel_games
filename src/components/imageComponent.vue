<script setup>
import { defineProps } from 'vue';

const props = defineProps({
    color: String
});
import imageGreen from '@/assets/SVG/Asset 1.svg'
import imageRed from '@/assets/SVG/Asset 2.svg'

</script>
<template>
    <img class="md:w-1/6 sm:w-2/12 w-1/12" :src="color === 'red' ? imageRed : imageGreen" alt="" />
</template>

  