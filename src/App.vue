<script setup>
//import { RouterLink, RouterView } from 'vue-router'
//import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <div class="wrapper">
      Hola soy la cabecera
    </div>
  </header>

  <RouterView />

</template>

<style scoped>
header {
  max-height: 100vh;
  border: 1px solid black;
  display: block;
  height: 20vh;
}
</style>
