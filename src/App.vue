<template>
  <div id="app">
    <Header />
    <Navbar />
    <Main />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Navbar from './components/Navbar.vue'
import Main from './components/Main.vue'

export default {
  name: 'app',
  components: {
    Header,
    Navbar,
    Main
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
#nav {
  padding-left: 0px;
}

#nav a {
  font-weight: bolder;
  color: #041b31;
}

#routerview {
  padding-top: 60px;
  padding-left: 50px;
  padding-right: 50px;
}

.header {
  padding-top: 25px;
  padding-bottom: 25px;
  text-align: center;
  font-size: 4em;
  background-color: rgb(223, 223, 223);
}

.projlist {
  list-style-type: none;
}

.projlist h1 {
  font-weight: bold;
}

li {
  padding-left: 25px;
  list-style-position: inside;
}

.main a{
  font-weight: bolder;
  color: #041b31;
}

</style>
