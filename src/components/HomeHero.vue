<template>
  <section class="home-hero">
    <div class="container">

      <div class="row justify-content-center">
        <img alt="MM" class="mmm-logo mb-5" src="../assets/logo.png">
      </div>
      <div class="row">
        <h1>{{ name }}</h1>
      </div>
      <div class="row title">
        <div class="col">
          web developer
        </div>
      </div>
      <div class="row location">
        <div class="col">
          based in Austin, TX
        </div>
      </div>
      <div class="row brand-statement">
        <div class="col-md-8 offset-md-2">
          <p>
            A mission-driven web developer, I am a pro at iterating and pivoting as project needs evolve, and I am committed to finding creative solutions.
          </p>
        </div>
      </div>
      <div class="row social-media justify-content-center">
        <div class="col-2">
          <a href="https://www.linkedin.com/in/meg-mansour/" target="_blank">
            <font-awesome-icon icon="fa-brands fa-linkedin-in" />
            LinkedIn
          </a>
        </div>
        <div class="col-2">
          <a href="https://github.com/megmaciver13" target="_blank">
            <font-awesome-icon icon="fa-brands fa-github" />
            GitHub
          </a>
        </div>
      </div>

    </div>
  </section>
</template>

<script>
export default {
  name: 'HomeHero',
  props: {
    name: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home-hero {
  background-color: #7FBACC;
}
.mmm-logo {
  max-width: 5rem;
  width: 100%;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
</style>
