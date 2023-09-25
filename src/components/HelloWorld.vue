<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1 class = "corfonte">{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++">contador de clicks {{ count }}</button>
    <p>
      Edit
      <code class = "corfonte">Um novo patamar</code> A Era Vue
    </p>
  </div>

 
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
.corfonte{
  color: azure;
}
</style>
