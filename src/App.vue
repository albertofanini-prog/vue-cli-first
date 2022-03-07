<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to my first Vue.js App"/>
    <HelloWorld text="This is my first try with Vue-Cli"/>
    <img id="mrBean" alt="mrBean" src="./assets/mr_bean.png">
    <HelloWorld dreamText="This is my dream car!"/>
    <img id="z4" alt="Z4" src="./assets/z4.png">
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
body{
  background-color: #2c3e50;
  color: white;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
#mrBean{
  border-radius: 999px;
}
#z4{
  width: 500px;
  height: 300px;
  border-radius: 25px;
}
</style>
