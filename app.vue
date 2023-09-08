<script setup>
import { ref } from 'vue';

const message = ref('Hello World');
</script>

<template>
  <div>
    <p>{{ message }}</p>
  </div>
</template>
