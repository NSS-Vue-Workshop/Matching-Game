<template>
  <div id="app">
    <matching-game />
  </div>
</template>

<script>
import MatchingGame from "./components/MatchingGame";

export default {
  name: "App",
  components: {
    MatchingGame
  }
};
</script>

<style>
body {
  background-color: #2c3e50;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
}
</style>
