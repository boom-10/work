<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <first></first>
    <second></second>
    <third></third>
    <four></four>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import first from './components/first'
import second from './components/second'
import third from './components/third'
import four from './components/four'
import './assets/adobe.css'
export default {
  name: 'App',
  components: {
    // HelloWorld,
    first,
    second,
    third,
    four
  }
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
