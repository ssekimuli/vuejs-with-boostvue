<template>
  <div id="app">
    <div>
  <b-navbar toggleable="lg" type="dark" variant="dark">
    <b-navbar-brand href="#">Vue</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="#">Home</b-nav-item>
      </b-navbar-nav>
      <b-navbar-nav>
        <b-nav-item href="#">our service</b-nav-item>
      </b-navbar-nav>
      <b-navbar-nav>
        <b-nav-item href="#">contact</b-nav-item>
      </b-navbar-nav>
      <b-navbar-nav>
        <b-nav-item href="#">aboutus</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
    <HelloWorld msg="Welcome vue"/>
   </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
