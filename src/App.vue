<template>
  <UserTitle userName="Thomas Testaud" userTitle="Développeur Web FullStack"/>
  <SkillsShapes/>
  <Portfolio/>  
  <BackGround/>
</template>

<script>
import BackGround from './components/BackGround.vue'
import UserTitle from './components/UserTitle.vue'
import SkillsShapes from './components/SkillsShapes.vue'
import Portfolio from './components/Portfolio.vue'

export default {
  name: 'App',
  components: {
    UserTitle,
    Portfolio,
    BackGround,
    SkillsShapes
  }
}
</script>

<style>
body {
    margin: 0;
    font-size: 16px;
    background-color: beige;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
