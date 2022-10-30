<script setup>
import { ref } from 'vue'
const count = ref(0)
</script>

<template>
  <footer>
    <button @click="count++">
      count is {{ count }}
    </button>
  </footer>
</template>

<style scoped>
footer {
  margin-top: 60vh;
  margin-bottom: 40px;
}

button {
  background: black;
  color: #eee;
  border: none;
  appearance: none;
  line-height: 20px;
  border-radius: 4px;
  height: 32px;
  padding: 0 1.4em;
}
</style>