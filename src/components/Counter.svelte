<script>
  let count = 0;

  const addToCount = () => {
    count = count + 1;
  };
</script>

<button on:click={addToCount}>clicka me</button>
<p>{count}</p>
