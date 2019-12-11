<template>
  <div id="app">
    <router-link v-bind:to="'/'">Home</router-link><br>
    <router-link v-bind:to="'/about'">About Vue</router-link>
    <!-- <a href="/"></a> -->
    <router-view usr="Fredrik"></router-view>
  </div>
</template>

<script>
// We dont need this one anymore, since we get it in our main.js instead
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  // Same with this one, no need for it.
  // components: {
  //   HelloWorld
  // }
}

</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
