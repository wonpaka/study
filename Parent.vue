<template>
  <div id="parent">
    <h1>Parent</h1>
    <input type="text">
    <Child/>
  </div>
</template>

<script>
import Child from './components/Child.vue'
export default {
  name:'Parent'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

#parent {
  margin: 1rem;
  border: 1px solid red;
}
</style>
