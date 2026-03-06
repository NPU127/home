<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    This is
    <code>NPU127</code>
    <p>
      <button type="button" @click="count++">Click me {{ count }} times!</button>
    </p>
  </div>

  <p>
    Check out
    <a href="https://blog.npu127.com" target="_blank"
      >my blog</a
    >!
  </p>
  <p>
    Learn more about me at
    <a
      href="https://github.com/NPU127"
      target="_blank"
      >my Github</a
    >.
  </p>
  <p class="read-the-docs">Click on the logo to learn more.</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
