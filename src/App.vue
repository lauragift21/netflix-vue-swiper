<template>
  <div id="app">
    <h1>{{ title }}</h1>
    <h3 style="color: white"><em>{{sub_title }}</em></h3>
    <HomePage/>
  </div>
</template>

<script>
import HomePage from './components/HomePage'

export default {
  name: 'App',
  components: {
    HomePage
  },
  data() {
    return {
      title : 'ScotchFlix',
      sub_title : 'Continue Watching'
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 20px;
  display: flex;
  align-items: center;
  flex-direction: column;
}

h1{
  color: #ffffff;
}
</style>
