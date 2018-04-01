<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div class="test-svg">
      <svg-icon icon-class="email"></svg-icon>
    </div>
    <div class="test-icon1">
      <svg-icon icon-class="kai"></svg-icon>
    </div>
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
.test-svg {
  width: 50px;
  height: 50px;
  color:aqua;
}
.test-icon1 {
  width: 30px;
  height: 30px;
  /* background-color: limegreen; */
}
</style>
