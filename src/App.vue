<template>
  <div id="app">
    <new-button></new-button>
  </div>
</template>

<script>

import NewButton from './components/NewButton.vue'
export default {
  name: 'App',
  components: {
    NewButton
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
