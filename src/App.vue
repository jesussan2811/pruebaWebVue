<template>
  <NaviBar msg="Welcome to Your Vue.js App"/>
  <NaviBar2 msg="Welcome to Your Vue.js App"/>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import NaviBar from './components/NaviBar.vue';
import NaviBar2 from './components/NaviBar2.vue';

export default {
  name: 'App',
  components: {
    NaviBar,
    NaviBar2
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
}
</style>
