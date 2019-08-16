<template>
  <div id="app">
    <Home/>
  </div>
</template>

<script>
import Home from './components/Home.vue'

export default {
  name: 'app',
  components: {
    Home
  }
}
</script>

<style>
@font-face {
  font-family: TitilliumWeb;
  font-weight: normal;
  src: url(assets/fonts/TitilliumWeb-Regular.ttf);
}

@font-face {
  font-family: TitilliumWeb;
  font-weight: bold;
  src: url(assets/fonts/TitilliumWeb-Bold.ttf);
}

#app {
  font-family: TitilliumWeb, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  height: 100vh;
}
</style>
