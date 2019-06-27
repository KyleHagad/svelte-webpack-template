<script>
  export let words = '';
</script>
  <h3>Tell me something!</h3>
  <input bind:value={words}>
{#if words.length > 0}
  <p>{words}!? Is that so?</p>
{/if}
