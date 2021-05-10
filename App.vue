<template>
  <div id="app">
    <h1>App</h1>
      <input type="text">
    <Parent/>
  </div>
</template>


<script>
// import HelloWorld from './components/HelloWorld.vue'
import Parent from './components/Parent.vue'

export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;

  /* 추가 */
  width: 500px;
  margin: 0 auto;
  border: 1px solid black;
  
}
</style>
