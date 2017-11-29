<template>
  <div id="app">
    <h1>Kanban-Fire</h1>
    <!-- <img src="./assets/logo.png" style="width:50px;"> -->
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /*margin-top: 60px;*/
}
h1 {
  background-image: linear-gradient(to right, red, orange 50%, brown);
  color: transparent;
  -webkit-background-clip: text;
  background-clip: text;
}
</style>
