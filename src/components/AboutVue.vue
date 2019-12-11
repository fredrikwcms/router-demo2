<template>
    <div id="about-vue">
        <h1>Welcome, {{ usr }}</h1>
        Vue.js is a fancy JavaScript framework. I love vue more than my life.
    </div>
</template>

<script>
export default {
    name: 'about',
    props: {
        usr: String
    }
}
</script>

<style>
#about {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>