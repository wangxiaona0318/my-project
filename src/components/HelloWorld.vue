<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential sdf</h2>
    <h2>Ecosystem</h2>
    <HelloIndex></HelloIndex>
  </div>
</template>

<script>
import HelloIndex from './HelloIndex'
export default {
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    HelloIndex
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
  font-size: inherit;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
