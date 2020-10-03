<script>
  export let fullname;
</script>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  .todos-container {
    margin: 0 auto;
    max-width: 600px;
  }

  .form-todo {
    margin: 1rem 0;
    border-radius: 4px;
    border: 1px solid #d3d3d3;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>

<main>
  <h1>Todo app</h1>
  <h2>{fullname}</h2>
  <button> Create Todo </button>
  <div class="todos-container">
    <div class="form-todo">
      <p>todo 1</p>
    </div>
    <div class="form-todo">
      <p>todo 2</p>
    </div>
  </div>
</main>
