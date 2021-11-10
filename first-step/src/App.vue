<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <Title msg="My first app with Vue CLI!!" />
    <!-- <Hero :src="img" /> -->
  </div>
</template>

<script>
// import Hero from "./components/Hero.vue";
import Title from "./components/Title.vue";
// import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    Title,
    // Hero,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
