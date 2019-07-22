<template>
  <div id="app">
    <create-input></create-input>
  </div>
</template>

<script>
import createInput from './components/second.vue'
export default {
  name: 'app',
  components: {
    createInput
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
