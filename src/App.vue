<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <Mixin />
  </div>
</template>

<script>
import Mixin from "./components/Mixin.vue";

export default {
  name: "App",
  components: {
    Mixin,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
