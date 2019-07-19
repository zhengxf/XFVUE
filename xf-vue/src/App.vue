<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
	
	
	/* 
	line-height:文字垂直居中 http://www.divcss5.com/rumen/r363.shtml
	
	旋转：
	transform:rotate(30deg);
	
	加边框
	border-width: 2px;
	border-style: solid;
	border-color: gray;
	
	
	
	*/
#app {
	
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>









