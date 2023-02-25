<script setup>
import { ref } from "vue";

const name = ref("My name");
</script>

<template>
  <div
    class="flex items-center bg-blue-600 text-4xl font-bold text-red-800 md:flex-col"
  >
    Tailwind is good by {{ name }}
  </div>
</template>

<style scoped></style>
