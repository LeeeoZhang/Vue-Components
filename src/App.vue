<template>
    <div id="app">
        <img src="./assets/logo.png">
        <Divider title="你好吗"/>
        <router-view/>
    </div>
</template>

<script>
  import Divider from './components/Divider/Divider'

  export default {
    components: {
      Divider,
    },
    name: 'App'
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
