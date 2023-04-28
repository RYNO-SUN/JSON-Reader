<script setup>
import HelloWorld from './components/HelloWorld.vue'
import race2 from './components/race2.vue'
import race3 from './components/race3.vue'
</script>

<template>
  
  <HelloWorld />
  <race2 />
  <race3  />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
