<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <h3>Mira nuestras redes</h3>

    <ul>
      <li>
        <a href="https://github.com/jp584/Vue1" target="_blank" rel="noopener">
          <img
            src="https://png.pngtree.com/png-vector/20221018/ourmid/pngtree-whatsapp-icon-png-image_6315990.png"
            alt=""
            class="iconos"
          />
        </a>
      </li>
      <li>
        <a href="https://github.com/jp584/Vue1" target="_blank" rel="noopener">
          <img
            src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png"
            alt=""
            class="iconos"
          />
        </a>
      </li>
      <li>
        <a href="https://github.com/jp584/Vue1" target="_blank" rel="noopener">
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/768px-LinkedIn_logo_initials.png"
            alt=""
            class="iconos"
          />
        </a>
      </li>
      <li>
        <a href="https://github.com/jp584/Vue1" target="_blank" rel="noopener">
          <img
            src="https://e7.pngegg.com/pngimages/625/935/png-clipart-google-surveys-google-docs-g-suite-form-formed-purple-violet-thumbnail.png"
            alt=""
            class="iconos"
          />
        </a>
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
.iconos {
  max-width: 100px;
  max-height: 100px;
}
</style>
