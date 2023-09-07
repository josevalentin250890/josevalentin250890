<script>
  let incount = 0
  const decrement = () => {
    incount -= 1
  }
</script>

<button on:click={decrement}>
  Incount is {incount}
</button>
