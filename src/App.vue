<template>
  <div id="app">
    <Landing msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import Landing from './components/landing.vue'

export default {
  name: 'App',
  components: {
    Landing
  }
}
</script>

<style>
@import './assets/style.css';
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
