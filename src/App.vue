<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <First msg="First Component" /> 
    <Users />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import First from './components/First.vue'
import Users from './components/Users.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    // First,
    Users
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
