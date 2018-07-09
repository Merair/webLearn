<template>
  <div id="app">
    <i class="icon iconfont icon-homepage"></i>
    <i class="icon iconfont icon-browse"></i>
    <i class="icon iconfont icon-service"></i>
    <i class="icon iconfont icon-people"></i>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
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
