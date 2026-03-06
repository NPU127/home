<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="https://npu127.com" target="_blank">
      <img src="/Cd.svg" class="logo" alt="NPU logo" />
    </a>
  </div>
  <HelloWorld msg="NPU127" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #ffff17aa);
}
</style>
