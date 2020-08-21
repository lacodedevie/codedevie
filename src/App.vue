<template>
  <div id="app">
    ``
    <Header />
    <question-block />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import QuestionBlock from "./components/QuestionBlock.vue";

export default {
  name: "App",
  components: {
    Header,
    QuestionBlock,
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
