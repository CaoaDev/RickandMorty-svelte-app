<script>
  export let character
</script>

<div class='character'>
  <img src={character.image} alt={character.name} />
  <h1>Personaje: {character.name}</h1>
  <h3>Especie: {character.species}</h3>
</div>
