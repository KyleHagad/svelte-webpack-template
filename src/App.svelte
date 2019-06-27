<script>
  export let name;
  import TalkBox from './TalkBox.svelte';
</script>

<style>
  h1 {
    color: purple;
  }
</style>

<h1>Hello {name}!</h1>
<p>What's Up?</p>
<div>
  <TalkBox/>
</div>
