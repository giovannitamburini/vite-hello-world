
<script>
// funzionalità
// importo il componente indicando il percorso e il nome
import Title from "./components/AppTitle.vue";
import Jumbotron from "./components/AppHero.vue";

export default {
  data() {
    return {

    };
  },
  // aggiungiamo il componente, fuori dai data in un oggetto apposito chiamato 'components'
  components: {
    Title,
    Jumbotron,
  },
};
</script>


<template>
  <!-- layout -->
  <!-- AppTitle -->
  <Title></Title>
  <!-- AppHero -->
  <Jumbotron></Jumbotron>
</template>

<style>
/* stile */
</style>