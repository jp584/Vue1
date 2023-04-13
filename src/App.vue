<template>
  <div id="app">
    <h1>BANCO MERCANTIL SANTA CRUZ</h1>

    <img
      alt="Vue logo"
      src="https://is4-ssl.mzstatic.com/image/thumb/Purple126/v4/a6/f6/bb/a6f6bbed-187e-b8b2-4622-36d44c4e8b2b/AppIcon-1x_U007emarketing-0-5-0-85-220.png/256x256bb.jpg"
    />



    
    <HelloWorld
      msg="Bienvenido Willy, estamos aqui para ayudarte a encontrar empleo"
    />
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

