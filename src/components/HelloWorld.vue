<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Banco BISA S.A. (antiguamente conocido como Banco Industrial S.A.), es una
      de las principales entidades financieras de Bolivia, con sede central en
      La Paz. Fundado el 5 de julio de 1963, Banco BISA es actualmente el cuarto
      banco más grande del país en términos de activos
      <a
        href="https://www.bisa.com/institucional"
        target="_blank"
        rel="noopener"
        >Página del banco</a
      >.
    </p>
    <h3>Video promocional</h3>
    <ul>
      <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/1WEAJ-DFkHE"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen
      ></iframe>
    </ul>
    <h3>Links al banco</h3>
    <ul>
      <li>
        <a href="https://www.bisa.com/" target="_blank" rel="noopener"
          >DIOS AYUDA</a
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
