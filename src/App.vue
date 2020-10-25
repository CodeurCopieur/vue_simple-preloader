<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Preloader></Preloader>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Preloader from './components/Preloader'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Preloader
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
  position: relative;
}
</style>
