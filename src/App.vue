<template>
  <my-modal />
</template>

<script>
import MyModal from './components/MyModal.vue'

export default {
  name: 'App',
  components: {
    MyModal
    
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
