<!-- <script lang="ts">
import { ref } from 'vue';

export default {
  setup() {
    const msg = ref('Hello Vue3');
    const count = ref(0);
    function increment() {
      count.value++;
    }
    return {
      count,
      msg,
      increment
    }
  }
}
</script>

<template>
  <h1 style="color: #333;">{{ msg }}</h1>
  <h1 style="color: #333;">{{ count }}</h1>
  <button @click="count++">{{ count }}</button>
  <button @click="increment">increment</button>
</template>

<style scoped>

</style> -->
<script setup lang="ts">
import { ref } from 'vue';

// const msg = ref('Hello Vue3');
const count = ref(0);
function increment() {
  console.log('increment', count.value);
  count.value++;
}
</script>

<template>
  <h1 style="color: #333;">{{ count }}</h1>
  <button @click="count++">{{ 'Add' }}</button>
  <button @click="increment">increment</button>
</template>