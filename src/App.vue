<template>
  <div>
    <WebSystem msg="Student Portfolio"/>
  </div>
</template>

<script>
import WebSystem from './components/WebSystem.vue'

export default {
  name: 'App',
  components: {
    WebSystem
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
}

</style>
