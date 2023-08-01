<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'

window.electronAPI.sendMessage('Hello from App.vue!');
</script>

<template>

  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>

</style>
