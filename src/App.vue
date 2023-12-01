<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {
  setup () {
    return {
      name: 'App'
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #312c50;
}
</style>
