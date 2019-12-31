<template>
  <div id="app">
    <TopHeader />
    <SideMenu />
    <MainDescription/>
  </div>
</template>

<script>
import TopHeader from './components/TopHeader.vue'
import SideMenu from './components/SideMenu.vue'
import MainDescription from './components/MainDescription.vue'

export default {
  name: 'app',
  components: {
    TopHeader,
    SideMenu,
    MainDescription
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
}
</style>
