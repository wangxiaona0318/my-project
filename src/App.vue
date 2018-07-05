<template>
  <div id="app">
    <div class="head"></div>
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style >
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

}
@media screen and (max-width: 414px){
  .head{
    height: 1rem;
    background: skyblue;
  }
}
</style>
