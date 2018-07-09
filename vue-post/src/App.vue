<template>
  <div id="app">
    <left-nav></left-nav>
    <div class="main">
      <router-view/>
    </div>
  </div>
</template>

<script>
import leftNav from '@/components/common/leftNav'
export default {
  name: 'App',
  components: {
    leftNav
  }
}
</script>

<style>
#app {
  font-family: 'Avenir';
  text-align: center;
  color: #2c3e50;
}
.main {
  float: left;
  width: 95%;
  height: 100%;
  background-color: rgb(240, 249, 255);
  overflow: hidden;
}
</style>
