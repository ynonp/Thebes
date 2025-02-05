<script setup lang="ts">
const count = ref(0);
</script>

<template>
  <h1>Welcome To Nuxt</h1>
  <button @click="count++">{{ count }}</button>
  <a href="/blog">Read My blog</a>
</template>
