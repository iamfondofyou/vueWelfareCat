<template>
  <div id="app">
    <router-view ></router-view>
    <router-view name="top"></router-view>
    <router-view name="main"></router-view>
    <router-view name="bottom"></router-view>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
html,body,#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffddce;
}
</style>
