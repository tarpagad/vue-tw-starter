<script setup>
import { ref } from "vue";

const name = ref("My name");
</script>

<template>
  <div class="text-4xl font-bold flex items-center text-red-800">
    Tailwind is good by {{ name }}
  </div>
</template>

<style scoped></style>
