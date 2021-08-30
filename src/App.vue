<template>
  <div id="app">
    <navigation-top></navigation-top>
    <router-view/>
    <footer-bottom></footer-bottom>
  </div>
</template>

<script>
import FooterBottom from './components/Footer.vue'
import NavigationTop from './components/Navigation.vue'
export default {
  components:{
    FooterBottom,
    NavigationTop
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

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
