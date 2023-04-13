<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <!--CARRUSEL INICIO-->
    <center>
      <div id="demo" class="carousel slide" data-ride="carousel">
        <!-- Barra de indicadores para ir a una imagen del Slide -->
        <ul class="carousel-indicators">
          <li data-target="#demo" data-slide-to="0" class="active"></li>
          <li data-target="#demo" data-slide-to="1"></li>
          <li data-target="#demo" data-slide-to="2"></li>
          <li data-target="#demo" data-slide-to="3"></li>
          <li data-target="#demo" data-slide-to="4"></li>
          <li data-target="#demo" data-slide-to="5"></li>
        </ul>
        <!-- Slide de Imagenes -->
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="embed-responsive embed-responsive-16by9">
              <iframe
                class="embed-responsive-item"
                src="https://www.youtube.com/watch?v=wglINoDCyFY"
                allowfullscreen
              ></iframe>
            </div>
          </div>
          <div class="carousel-item">
            <img src="img/2.jpg" alt="Chicago" width="800" height="450" />
          </div>
          <div class="carousel-item">
            <img src="img/3.jpg" alt="New York" width="800" height="450" />
          </div>
          <div class="carousel-item">
            <img src="img/4.jpg" alt="New York" width="800" height="450" />
          </div>
          <div class="carousel-item">
            <img src="img/5.jpg" alt="New York" width="800" height="450" />
          </div>
          <div class="carousel-item">
            <img src="img/6.jpg" alt="New York" width="800" height="450" />
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
    <p>
      For a guide and recipes on how to configure / customize this project,<br />
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener"
        >vue-cli documentation</a
      >.
    </p>
    <h3>Mira neustras redes</h3>

    <ul>
      <li>
        <a
          href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel"
          target="_blank"
          rel="noopener"
          >babel

          <img src="" alt="" />
        </a>
      </li>
      <li>
        <a
          href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint"
          target="_blank"
          rel="noopener"
          >eslint</a
        >
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
