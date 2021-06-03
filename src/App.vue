<template>
  <div id="app">
    <Header />
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <figure>
      <img class='img' alt="Vue logo" src="./assets/fotoLab.png">
    </figure>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    Header,
    HelloWorld,
  }
}
</script>

<style>
*{
  margin: 0;
	padding: 0;
	border: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
figure{
  background-color: rgba(247, 247, 247, 0.651);
}
.img{
  width: 50%
}
</style>
