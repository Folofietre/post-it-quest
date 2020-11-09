<template>
  <div id="app">
    <ResourceMenu></ResourceMenu>
  </div>
</template>

<script>
import ResourceMenu from './components/Menu/ResourceMenu/ResourceMenu.vue'

export default {
  name: 'app',
  components: {
    ResourceMenu
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
