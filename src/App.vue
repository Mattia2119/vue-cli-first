<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <PrimoComponente/>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import PrimoComponente from './components/PrimoComponente.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    PrimoComponente
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
