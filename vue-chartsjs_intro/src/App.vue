<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to the Vue Charts.JS Playground"/>
    <bar-chart/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import BarChart from './components/BarChart.vue'

export default {
  name: 'App',
  components: {
    HelloWorld, BarChart
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
