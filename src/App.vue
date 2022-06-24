<template>
  <!--<img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>-->
  <test-vue></test-vue>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import testVue from './components/test_vue.vue'

export default {
  name: 'App',
  components: {
    //HelloWorld,
    testVue
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
