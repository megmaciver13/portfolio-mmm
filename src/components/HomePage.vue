<template>
  <h1>{{ name }}</h1>
  <div class="location">
    based in Austin, TX
  </div>
  <div class="brand-statement">
    <p>
      A mission-driven web developer, I am a pro at iterating and pivoting as project needs evolve, and I am committed to finding creative solutions.
    </p>
  </div>
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
