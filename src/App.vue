<template>
  <div id="app">
    <Header></Header>
    <router-view />
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/Header'
import Footer from './components/Footer'
export default {
  name: "App",
  components: {
    Header,
    Footer
  },
};
</script>

<style>
html,
body {
  margin: 0;
  padding: 0;
  background-color: rgb(244, 245, 247);
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  font-size: 12px;
  color: #222;
}
</style>
