<template>
  <div>
    <h1>Hello World</h1>
    <!-- <NuxtWelcome /> -->
  </div>
</template>
<script setup lang="ts">
function greet(name: string) {
  console.log(`Hello, ${name}!`);
}

const age = '25'; // This should be a string

greet(age);
</script>
