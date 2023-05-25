<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>
 <p>
    Powered by
    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank"
      >create-vue</a
    >, the official Vue + Vite source. 
  </p>
  <p>
    Integrated with
    <a href="https://github.com/vuejs/language-tools" target="_blank">Volar</a>
    IDE for a better DX.
  </p>
  <p class="read-the-docs">Good DX means DevOps can seamlessly <code>package.json</code> this technology within their projects. This interoperable framework is flexible to evaluate, install, test, integrate, and maintain cross-platform W3C standardization.</p>
  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>
     Adam's <code>Web3.0</code> Vue app rendering Vite interactive components. 
     <p> Visit <code>components/adamsworld.vue</code> for Vue proof of concept.</p>
    </p>
  </div>

 
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
