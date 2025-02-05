<script setup lang="ts">
const count = ref(0);
</script>

<template>
  <h1>Welcome To Nuxt</h1>
  <div class="flex">
    <button @click="count++">{{ count }}</button>
    <a href="/blog">Read My blog</a>
  </div>
</template>

<style lang="css" scoped>
  .flex {
    display: flex;
  }

  .flex * {
    flex: 1;
  }

</style>