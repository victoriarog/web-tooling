<script setup lang="ts">
import { ref } from "vue";

// defineProps<{ msg: string }>()

const count = ref(0);
</script>

<template>
  <!-- <h1>{{ msg }}</h1> -->

  <div class="card">
    <h2>Click me to count</h2>
    <button type="button" @click="count++">click me</button>
    <button type="button" @click="count = 0">reset</button>
    <br />
    <p>count is {{ count }}</p>
  </div>
</template>
