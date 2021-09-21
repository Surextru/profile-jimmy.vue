<template>
  <div id="app">
    <AboutMe></AboutMe>
    <Projects></Projects>
  </div>
</template>

<script>
import Projects from "./components/Projects.vue"
import AboutMe from "./components/AboutMe.vue"
export default {
  name: 'App',
  components: {
    Projects,
    AboutMe
  }
}
</script>

<style>

</style>
