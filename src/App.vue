<template>
  <div id="app">
    <CodeRegion/>
  </div>
</template>

<script>
import CodeRegion from './components/CodeRegion'

export default {
  name: 'App',
  components: {
    CodeRegion
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
