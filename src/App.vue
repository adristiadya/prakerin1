<template>
  <div id="app">
    <img alt="Telkom Schools" src="https://www.dbl.id/uploads/school/26500/99-SMK_TELKOM_MAKASSAR.PNG">
    <HelloWorld msg="Telkom Schools"/>
    <tombol class="btn btn-danger"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import tombol from './components/tombol.vue'
import 'bootstrap/dist/css/bootstrap.css';
import 'bootstrap/dist/js/bootstrap.js';

export default {
  name: 'App',
  components: {
    HelloWorld,
    tombol,
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
