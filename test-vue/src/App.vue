<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <myComponents></myComponents>
</template>

<script>
import myComponents from './components/myComponents.vue'

export default {
  name: 'App',
  components: {
    myComponents
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
