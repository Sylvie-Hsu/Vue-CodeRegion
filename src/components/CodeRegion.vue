<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential Samples</h2>
  </div>
</template>

<script>
export default {
  name: 'CodeRegion',
  data () {
    return {
      msg: 'Welcome to CodeRegion'
    }
  }
}
</script>

<style scoped>
h1, h2 {
  font-weight: normal;
}
</style>
