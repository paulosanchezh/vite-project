<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1 class="title">Hola a my project</h1> 
</template>

<style scoped>
  .title {
    background-color: black;
    color: white;
  }
</style>
