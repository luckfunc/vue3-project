<script setup lang="ts">
import { ref } from 'vue';
const count = ref('Hello Vue3');
console.log(count.value);
</script>

<template>
  <span>message {{ 'Hello Vue3' }}</span>
</template>

<style scoped>

</style>
