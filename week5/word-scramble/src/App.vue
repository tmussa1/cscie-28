<template>
  <div id="app">
    <WordScramble msg="Word Scramble" />
  </div>
</template>

<script>
import WordScramble from "./components/WordScramble.vue";

export default {
  name: "App",
  components: {
    WordScramble
  }
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
