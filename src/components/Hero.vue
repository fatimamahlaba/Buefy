<template>
  <div class="hero is-primary is-midhieght is-bold">
    <div class="hero-body">
      <div class="container has-text-centered">
       <h1 class="title">{{ title }}</h1>
       <p class="is-size-4">{{ msg }}</p>
       <a href="#contactForm" class="button m-t-30">Contact Us</a>
    </div>
    </div>
  </div>
</template>

<script>
/* eslint-disable */
export default {
  name: 'Hero',
  props: {
    title: String,
    msg: String
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

</style>
