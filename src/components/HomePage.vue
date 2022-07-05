<template>
  <section>
    <div class="container">

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
          <a href="https://www.linkedin.com/in/meg-mansour/" target="_blank">LinkedIn</a>
        </div>
        <div class="col-2">
          <a href="https://github.com/megmaciver13" target="_blank">GitHub</a>
        </div>
      </div>

    </div>
  </section>
</template>

<script>
export default {
  name: 'HomePage',
  props: {
    name: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
