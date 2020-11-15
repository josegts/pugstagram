<script>
  import Card from "./Card.svelte";
  export let posts = []

</script>

<div class="Timeline">
  <section class="Timeline-cont">
    {#each posts as post}
      <Card {...post}/>
    {:else} 
      <span>Loading...</span>
    {/each}
  </section>
</div>

<style>
  .Timeline {
    padding: 4em 0 0 0;
  }
</style>