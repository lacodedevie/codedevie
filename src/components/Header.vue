<template>
  <div class="navs">
    <b-nav tabs sm="6" offset="3">
      <b-nav-item id="id-1" disabled><h1>The Quiz</h1></b-nav-item>
      <b-nav-item id="id-2" disabled
        >Counter: {{ numCorrect }}/{{ numTotal }}</b-nav-item
      >
    </b-nav>
  </div>
</template>

<script>
export default {
  props: ["numCorrect", "numTotal"],
};
</script>
<style scoped>
.nav-tabs .nav-item {
  display: flex;
  flex-wrap: wrap;
  align-content: center;
  flex-direction: row;
  color: black;
  text-align: center;
}
.navs {
  background-color: skyblue;
  display: inline-block;
  border-radius: 20px;
}
</style>
