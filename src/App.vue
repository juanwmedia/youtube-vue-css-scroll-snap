<template>
  <div id="app">
    <AppSlider/>
  </div>
</template>

<script>

import AppSlider from './components/AppSlider.vue';
export default {
  name: 'App',
  components: {
    AppSlider
  }
}

</script>

<style>
html, body {
  height: 100%;
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
