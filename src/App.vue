<template>
  <NavBar />
  <HomeHero name="Meg Mansour"/>
  <AboutMe id="about" />
  <MyResume id="resume" />

  <!-- <button @click="alertMessage">Alert</button> -->
</template>

<script>
import NavBar from './components/NavBar.vue'
import HomeHero from './components/HomeHero.vue'
import AboutMe from './components/AboutMe.vue'
import MyResume from './components/MyResume.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    NavBar,
    HomeHero,
    AboutMe,
    MyResume
  },
  data(){
    return {
      message: 'Hello MegWorld!'
    }
  },
  methods: {
    alertMessage(){
      alert(this.message)
    }
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

section {
  padding-top: 4rem;
  padding-bottom: 4rem;
}
a {
  color: #378F93;
  text-decoration: none;
}
a:hover {
  color: #425267;
}
</style>
