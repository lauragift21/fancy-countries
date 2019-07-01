<template>
  <div id="app">
    <AppNav />
  </div>
</template>

<script>
import AppNav from "./components/AppNav.vue";

export default {
  name: "app",
  components: {
    AppNav
  }
};
</script>

<style>
#app {
  max-width: 1300px;
  margin: 0 auto;
  font-family: 'Nunito Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #48494b;
}
</style>
