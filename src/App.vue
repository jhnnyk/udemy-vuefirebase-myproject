<template>
  <div id="app">
    <h1>{{ title }}</h1>
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>-->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: "app",
  // components: {
  //   HelloWorld
  // }
  data() {
    return {
      title: "My first Vue app, woooo :-)"
    };
  }
};
</script>

<style>
h1 {
  color: #444;
  font-weight: normal;
  text-align: center;
}
</style>
