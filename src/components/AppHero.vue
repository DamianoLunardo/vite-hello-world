<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>
  <div></div>
</template>

<style scoped>
  div {
    background-image: url(occhio.jpg);
    height: 100vh;
  }
</style>