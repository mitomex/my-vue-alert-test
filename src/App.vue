<template>
  <div id="app">
    <AlertTest />
  </div>
</template>

<script>
import AlertTest from "./components/AlertTest";

export default {
  name: "app",
  components: {
    AlertTest
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
