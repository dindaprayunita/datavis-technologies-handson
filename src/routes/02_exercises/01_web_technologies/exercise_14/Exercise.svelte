<script>
  let current = "";
</script>

<style>
  .background {
    background-color: red;
  }
</style>

<!-- We will cover buttons later on! -->
<button class="btn btn-secondary"  class:background={current == "messi"} on:click={() => (current = "messi")}>
  Messi
</button>

<button class="btn btn-secondary" class:background={current == "ronaldo"} on:click={() => (current = "ronaldo")}>
  Ronaldo
</button>

<button class="btn btn-secondary" class:background={current == "neymar"} on:click={() => (current = "neymar")}>
  Neymar
</button>
