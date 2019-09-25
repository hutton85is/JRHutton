<template>
  <div id="app">
    <Header />
    <Navbar />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Navbar from './components/Navbar.vue'

export default {
  name: 'app',
  components: {
    Header,
    Navbar
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
  font-weight: bold;
  color: #041b31;
}

#nav a.router-link-exact-active {
  text-decoration: underline;
  font-weight: bolder;
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

</style>
