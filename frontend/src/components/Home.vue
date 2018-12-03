<template>
<div>
  <h1>
    <span class="deeppink">BEST</span>
    <span class="yellow">EVER</span>
    <span class="deeppink">COLORS</span>
  </h1>
  <ul class="list"></ul>
  <div class="add-color-wrapper">
    <span class="add-color-text crimson">Add color: </span>
    <input type="text"/>
  </div>
</div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss" scoped>
body {
	background: deepskyblue;
	font-family: Verdana, Geneva, Tahoma, sans-serif;
}

.list {
	border: 5px solid gold;
	width: 250px;
	color: white;
	text-align: center;
	font-size: 25px;
	line-height: 1.5;
	padding: 15px;
	list-style-type: none;
	margin: 10px auto 0;
}

.add-color-wrapper {
	margin-top: 20px;
	text-align: center;
}

.add-color-text {
	font-weight: 700;
	font-size: 19px;
}

h1 {
	font-size: 45px;
	text-align: center;
}

input {
	width: 200px;
	height: 26px;
	padding-left: 10px;
	color: limegreen;
	border-radius: 10px;
	border: none;
	font-size: 16px;
	font-weight: bold;
}

.deeppink {
	color: deeppink;
}

.yellow {
	color: yellow;
}

.crimson{
	color: crimson;
}

.error { 
	color: red;
	font-size: 20px;
	border: 5px solid orange;
	padding: 15px;
	margin: 0 auto;
	text-align: center;
	width: 350px;
}
</style>
