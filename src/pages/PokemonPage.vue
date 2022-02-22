<template>
  <h1>¿Quie es este Pokemon?</h1>

  <!-- TODO: img-->
  <pokemon-picture :pokemonId="156" :showPokemon="true" />

  <!-- TODO: Opciones-->
  <pokemon-options />

</template>

<script>
import PokemonOptions from "@/components/PokemonOptions";
import PokemonPicture from "@/components/PokemonPicture";

export default {
  name: "PokemonPage",
  components:{
    PokemonPicture,
    PokemonOptions
  }
}
</script>