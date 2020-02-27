<template>
  <div id="app">
    <navigation/>
    <router-view></router-view>
    <Footer/>
    
  </div>
</template>

<script>
import Navigation from './components/includes/nav.vue'
import Footer from './components/includes/footer.vue'

export default {
  name: 'App',
  components: {
    Navigation,
    Footer

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
