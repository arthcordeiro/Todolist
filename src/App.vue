<template>
  <div id="app">
    <img class="logo" alt="Vue logo" src="./assets/logo.png">
    <todolist />
  </div>
</template>

<script>
import todolist from './components/Todolist.vue'

export default {
  name: 'app',
  components: {
    todolist
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  font-size: 24px;
}

.logo{
  display: block;
  margin: 20px auto;
  height: 75px;
}
</style>
