<script>
  export let count = 0;

  const clickHandler = () => { count += 1; }
</script>

<button on:click={clickHandler}>Increment!</button>
<p>{count}</p>
