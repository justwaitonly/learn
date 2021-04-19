<template>
  <div id="app">
    <div>未来，你好，我是现在的自己!!!!!!!!</div>
   <index></index>
  </div>
</template>

<script>
import index from './Form/index.vue'

export default {
  name: 'App',
  components: {
    index
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
}
</style>
