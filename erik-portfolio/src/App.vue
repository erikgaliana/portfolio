<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Portfolio msg="Erik Galiana - Full Stack Developer"/>
  </div>
</template>

<script>
import Portfolio from './components/Portfolio.vue'

export default {
  name: 'app',
  components: {
    Portfolio
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
