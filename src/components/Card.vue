<script>

</script>


<template>


  <grid>
    <img :src = "url" alt ="nombre">

    <h2>{{nombre}}</h2>

    <a :href="url" target="_blank"> Descargar </a>

  </grid>

</template>


<style scoped>

  img {
    width: 8rem;
    height: 8rem;
    padding: 0.5rem;
    background: snow;

  }

  a {
    text-decoration: none;
    color: snow;
    background: purple;
    padding: 0.3rem;
    border-radius: 1px;

  }
</style>


<script>

  import Grid from "./Grid.vue";

  export default {
    props: {
      url: {
        String,
      },
      nombre: {
        String,
      },
    },
    Components: {
      Grid,
    },
  };
</script>