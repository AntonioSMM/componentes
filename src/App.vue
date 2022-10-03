<template>

  <h1>Componentes</h1>

  <hr>

  <Card url="https://cdn.svgporn.com/logos/vue.svg?response-content-disposition=attachment%3Bfilename%3Dvue.svg" nombre = "Vue.js"> </Card>
  <Card url="https://cdn.svgporn.com/logos/vuetifyjs.svg?response-content-disposition=attachment%3Bfilename%3Dvuetifyjs.svg" nombre="Vuetify"> </Card>
  <Card url="https://cdn.svgporn.com/logos/angular-icon.svg?response-content-disposition=attachment%3Bfilename%3Dangular-icon.svg" nombre="Angular"> </Card>
  <Card url="https://cdn.svgporn.com/logos/react-query-icon.svg?response-content-disposition=attachment%3Bfilename%3Dreact-query-icon.svg" nombre="React"> </Card>
  <Card url="https://cdn.svgporn.com/logos/react-spring.svg?response-content-disposition=attachment%3Bfilename%3Dreact-spring.svg" nombre="React Spring"> </Card>
 


</template>


<script>
  import Card from "./components/Card.vue"

  export default {
    components: {
      Card
    },
  };
</script>