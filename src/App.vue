<template>
  <div id="app">
    <h1>BANCO MERCANTIL SANTA CRUZ</h1>

    <img
      alt="Vue logo"
      src="https://is4-ssl.mzstatic.com/image/thumb/Purple126/v4/a6/f6/bb/a6f6bbed-187e-b8b2-4622-36d44c4e8b2b/AppIcon-1x_U007emarketing-0-5-0-85-220.png/256x256bb.jpg"
    />
     <!--CARRUSEL INICIO-->
    <center>
      <div id="demo" class="carousel slide" data-ride="carousel">
        <!-- Barra de indicadores para ir a una imagen del Slide -->
        <ul class="carousel-indicators">
          <li data-target="#demo" data-slide-to="0" class="active"></li>
          <li data-target="#demo" data-slide-to="1"></li>
          <li data-target="#demo" data-slide-to="2"></li>
        </ul>
        <!-- Slide de Imagenes -->
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img
              src="https://lpz.ucb.edu.bo/wp-content/uploads/2021/10/Mercantil-Santa-Cruz.png"
              alt="Los Angeles"
              width="800"
              height="450"
            />
          </div>
          <div class="carousel-item">
            <img
              src="https://jornada.com.bo/wp-content/uploads/2022/08/El-Banco-Mercantil-Santa-Cruz-lanza-un-nuevo-Seguro-Vehicular-con-pago-en-cuotas-mensuales.jpeg"
              alt="Chicago"
              width="800"
              height="450"
            />
          </div>
          <div class="carousel-item">
            <img
              src="https://boliviaemprende.com/wp-content/uploads/2015/10/banco-mercantil.jpg"
              alt="New York"
              width="800"
              height="450"
            />
          </div>
        </div>
        <!-- Controles para desplazar imagenes Izquierda o Derecha -->
        <a class="carousel-control-prev" href="#demo" data-slide="prev">
          <span class="carousel-control-prev-icon"></span>
        </a>
        <a class="carousel-control-next" href="#demo" data-slide="next">
          <span class="carousel-control-next-icon"></span>
        </a>
      </div>
    </center>
    <!--CARRUSEL FIN-->
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
