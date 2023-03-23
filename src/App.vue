
<script>
// funzionalità
// importo il componente indicando il percorso e il nome
import Title from "./components/AppTitle.vue";

export default {
  data() {
    return {

    };
  },
  // aggiungiamo il componente, fuori dai data in un oggetto apposito chiamato 'components'
  components: {
    Title,
  },
};
</script>


<template>
  <!-- layout -->
  <Title></Title>
</template>

<style>
/* stile */
</style>