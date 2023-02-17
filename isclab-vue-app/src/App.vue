<template>
  <span class="inline-flex items-baseline">
    <img alt="ISC logo" class="w-40 h-auto self-center items-center pb-4" src="./assets/ISCLogo.png">
  </span>
  <h1 class="text-[50px]">ISC LAB</h1>
  <HelloWorld msg=""/>
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
