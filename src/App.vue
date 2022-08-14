<template>
  <LandingPage />

</template>

<script>
import LandingPage from './components/LandingPage.vue';

export default {
  name: 'App',
  components: {
    LandingPage
  }
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  display: inline;
  margin: 0;
  padding: 0;
}

body {
  margin: 0;
  padding: 0;
  background-color: rgba(255, 255, 255, 0.37);
  box-sizing: border-box;
  top: 0px;
}

</style>
