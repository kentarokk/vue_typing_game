<template>
  <div id="app">
    <TypingGame />
  </div>
</template>

<script>
import TypingGame from "./components/TypingGame.vue";

export default {
  name: "App",
  components: {
    TypingGame,
  },
};
</script>

<style>
#app {
  font-family: Arial, Helvetica, sans-serif;
  /* font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center; */
  color: #2c3e50;
}
</style>
