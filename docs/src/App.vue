<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="https://vite.dev" target="_blank">
      <img src="./assets/logo.svg" class="logo" alt="ChatNext" />
    </a>
  </div>
  <h1>
    专为
    <span contenteditable>AI 对话</span>
    设计的高效组件库
  </h1>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #165dff);
}
</style>
