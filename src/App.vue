<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <MainCard/>
  <ProjectCard/>
</template>

<script>
import MainCard from './components/MainCard.vue';
import ProjectCard from './components/ProjectCard.vue';

export default {
  name: 'App',
  components: {
    MainCard,
    ProjectCard
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
</style>
