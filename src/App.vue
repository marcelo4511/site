<template>
  <div id="app">
    <HeaderLayout />
    <MainContent />
    <FooterLayout />
  </div>
</template>

<script>
import HeaderLayout from './components/HeaderLayout.vue'
import MainContent from './components/MainContent.vue'
import FooterLayout from './components/FooterLayout.vue'

export default {
  name: 'App',
  components: {
      HeaderLayout,
      MainContent,
      FooterLayout
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
}
</style>