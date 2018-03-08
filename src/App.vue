<template>
  <div id="app">
    <percentage :used="used" :free="free" :usedColor="usedColor"
      :freeColor="freeColor" :lineWidth="lineWidth" :height="height"
      :width="width"></percentage>
  </div>
</template>

<script>
import percentage from './components/percentage.vue'

export default {
  name: 'app',
  components: {
    percentage
  },
  data () {
    return {
      used: 2.5,
      free: 0.5,
      usedColor: '#ff6100',
      freeColor: '#ddd',
      lineWidth: 20.0,
      height: 300,
      width: 300
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
  margin-top: 60px;
}
</style>
