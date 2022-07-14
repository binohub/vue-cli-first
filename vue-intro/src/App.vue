<template>
  <div id="app">

    <div class="jumbotron jumbotron-fluid bg-dark">
      <div class="container">
        <h1 class="display-4">Fluid jumbotron</h1>
        <p class="lead">This is a modified jumbotron that occupies the entire horizontal space of its parent.</p>
      </div>
    </div>

    <TitleMain msg="Welcome to Your Vue.js App" />

  </div>
</template>

<script>
import TitleMain from './components/TitleMain.vue'

export default {
  name: 'App',
  components: {
    TitleMain
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
