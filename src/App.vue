<script setup>
  import { ref } from 'vue';

  const date = ref(new Date())
</script>

<template>
  <div>{{ date }}</div>
</template>

<style scoped></style>
