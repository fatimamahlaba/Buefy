<template>
  <div id="app">
    <Hero msg="Hello world. Lorem ipsum text." title="Welcome to your Vue.js App"/>
    <Contact title="Contact Us"/>
  </div>
</template>

<script>
import Hero from './components/Hero.vue'
import Contact from './components/Contact.vue'

export default {
  name: 'App',
  components: {
    Hero,
    Contact
  }
}
</script>

<style>

</style>
