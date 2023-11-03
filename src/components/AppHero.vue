<script setup>
import { ref } from 'vue'

defineProps({
  ciao: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ ciao }}</h1>
 
</template>

<style scoped>
  h1 {
    background-image: url(occhio.jpg);
    height: 100vh;
    color: white;
  }
</style>