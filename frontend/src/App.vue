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
</style>
