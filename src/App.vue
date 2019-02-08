<template>
  <div id="app">
    <h1>Cash Verification</h1>
    <Cash />
  </div>
</template>

<script>
import Cash from "./components/Cash";

export default {
  name: "App",
  components: {
    Cash
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
h1 {
  text-align: center;
}
</style>
