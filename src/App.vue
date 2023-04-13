<template>
  <div id="app">
    <img alt="Vue logo" src="https://th.bing.com/th/id/R.76b3145515e1884e3a041c2b8129b1b5?rik=0p%2bOIRuSjYg5uw&riu=http%3a%2f%2fitc-bolivia.com%2fwp-content%2fuploads%2f2019%2f05%2fBanco-Bisa.png&ehk=%2bzecoIz8KnbwJT96meFgbnM4Mb05rQOFm5b3z35coKI%3d&risl=&pid=ImgRaw&r=0" />
    <HelloWorld msg="Bienvenido a Banco Bisa" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
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
