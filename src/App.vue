<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/meitaku.jpg" style="width: 300px; height: 400px; margin-right: 50px;">
    <img alt="Vue logo" src="./assets/meitaku2.jpg" style="width: 300px; height: 400px; margin-right: 50px;">
    <img alt="Vue logo" src="./assets/meitaku3.jpg" style="width: 300px; height: 400px;">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
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
