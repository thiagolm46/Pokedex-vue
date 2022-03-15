<template>
  <div id="app">
    <PokemonIndex />
  </div>
</template>

<script>
import PokemonIndex from './components/PokemonIndex.vue'

export default {
  components: {
    PokemonIndex
  }
}
</script>

<style>
  @import url('https://use.fontawesome.com/releases/v5.8.2/css/all.css');

  body {
    margin: 0;
    padding: 0;
  }
</style>