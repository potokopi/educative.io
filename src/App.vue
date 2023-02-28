<template>
  <NavBar></NavBar>
  <router-view></router-view>
  <FooterTemplate></FooterTemplate>
</template>

<script>
import NavBar from './components/NavBar.vue'
import FooterTemplate from './components/FooterTemplate.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    FooterTemplate
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
