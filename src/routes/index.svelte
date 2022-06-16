<script>
  let title = "Ninja Gaming Guides";

  const updateTitle = () => {
    title = "something completely different";
  };
</script>

<div class="index">
  <h2>{title}</h2>
  <p>
    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Asperiores, in
    ratione quod libero voluptate saepe minus esse facere, eveniet fuga quas
    sint eum blanditiis, molestias tempore deserunt id labore. Architecto.
  </p>

  <button on:click={updateTitle}>Change Title</button>
  <input type="text" bind:value={title} />
</div>

<style>
  .index {
    text-align: center;
    display: block;
    margin: 20px auto;
  }
</style>
