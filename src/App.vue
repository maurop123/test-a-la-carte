<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>

    <div class="card">
    </div>

    <date-picker />
  </div>
</template>

<script>
  import DatePicker from './components/DatePicker'
  export default {
    name: 'app',
    components: {
      DatePicker,
    },
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>

<style scoped>
  .card {
    height: 100px;
    width: 100px;
    background-color: red;
  }
</style>
