<script>
  let songs = [
    "Blinding Lights",
    "Save Your Tears",
    "In the Night",
    "Starboy",
    "I Feel It Coming",
    "The Hills",
  ];
</script>

<div class="song-list">
  <h2>Canciones Populares</h2>
  <ul>
    {#each songs as song}
      <li>{song}</li>
    {/each}
  </ul>
</div>

<style>
  .song-list {
    text-align: center;
    padding: 20px;
  }
</style>
