<template>
  <div id="app">
    <NavigationBar />
    <Jumbo /> <br/>
    <CardsGrid /> <br/>
    <!-- <SideBar /> -->
    <Formcontrol /> 
  </div>
</template>

<script>
import NavigationBar from './components/NavigationBar.vue'
import Jumbo from './components/Jumbo.vue'
import CardsGrid from './components/CardsGrid.vue'
// import SideBar from './components/SideBar.vue'
import Formcontrol from './components/Formcontrol.vue'

export default {
  name: 'App',
  components: {
    NavigationBar,
    Jumbo,
    CardsGrid,
    // SideBar,
    Formcontrol
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
  margin-top: 2px;
  background-color: #bddbc8
}
</style>
