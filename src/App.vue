<template>
  <div id="app">
    <img alt="Vue logo" src="https://vuejs.org/images/logo.png" />
    <HelloWorld msg="Hällo WPG7" />
    <Raten msg="Versuche die Zahl zu erraten!" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Raten from './components/Raten.vue';
export default {
  name: 'App',
  components: {
    HelloWorld,
    Raten,
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
