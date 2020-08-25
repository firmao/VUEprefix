<template>
  <div id="app">
    <prefix-auto/>
  </div>
</template>

<script>
import prefixAuto from './components/prefixComplete.vue'

export default {
  name: 'App',
  components: {
    prefixAuto
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
