<template>
  <div id="app">
    <Home/>
  </div>
</template>

<script>
  import Home from './components/Home.vue'
  export default {
    name: 'App',
    components: {
      Home
    }
  }
</script>

<style>
body {
	background: deepskyblue;
	font-family: Verdana, Geneva, Tahoma, sans-serif;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
