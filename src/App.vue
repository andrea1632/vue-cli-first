<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <TitleMain></TitleMain>
    <HeroSection></HeroSection>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import TitleMain from './components/TitleMain.vue'
import HeroSection from './components/jumbotron.vue'

export default {
  name: 'App',
  components: {
    //HelloWorld
    TitleMain, 
    HeroSection
  }
}
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
