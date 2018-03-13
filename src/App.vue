<template>
  <div>
    <header-view/>
    <router-view/>
    <footer-view/>
  </div>
</template>

<script>
import headerView from './components/header'
import footerView from './components/footer'
export default {
  name: 'App',
  components: {
    headerView,
    footerView
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
