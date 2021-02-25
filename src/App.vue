<template>
  <div id="app" class="qq2q1qq">
    <img src="./assets/logo.png">
    <add></add>
    <router-link to='/sub'>aaaa</router-link>
    <router-view/>
  </div>
</template>

<script>
import add from './components/add.vue'
export default {
  name: 'App',
  components: {
    add
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
