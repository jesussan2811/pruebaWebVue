<template>
  <OfertaEmergente msg="listo"/>
  <Navbar msg="Welcome to Your Vue.js App"/>
  <Navbar2 msg="Welcome to Your Vue.js App"/>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/Navbar.vue';
import Navbar2 from './components/Navbar2.vue';
import OfertaEmergente from './components/OfertaEmergente.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Navbar2,
    OfertaEmergente,
  }
}
</script>

<style>
#app {
  font-family: system-ui,sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
