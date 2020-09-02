<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Product msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import Product from './components/Product.vue'

export default {
  name: 'App',
  components: {
    Product
  }
}
</script>

<style>
#app {
  font-family: Montserrat;
  -webkit-font-smoothing: Montserrat;
  -moz-osx-font-smoothing: Montserrat;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
