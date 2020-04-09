<template>
  <div class="container">
    <div>
      <p align="center"><img src="~/static/icon.png" alt="Logo" width="128" height="128" style="max-width: 100%;"></p>
      <h1 class="title">
        [WIP] MoeToolbox
      </h1>
      <h2 class="subtitle">
        Awesome modern toolbox webapp.
      </h2>
      <div class="links">
        <a
          href="https://github.com/boxlab/MoeToolbox"
          target="_blank"
          class="button--grey"
        >
          GitHub
        </a>
      </div>
    </div>
  </div>
</template>

<script>
  export default {}
</script>

<style>
  .container {
    margin: 0 auto;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }

  .title {
    font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    display: block;
    font-weight: 300;
    font-size: 50px;
    color: #35495e;
    letter-spacing: 1px;
  }

  .subtitle {
    font-weight: 300;
    font-size: 30px;
    color: #526488;
    word-spacing: 5px;
    padding-bottom: 15px;
  }

  .links {
    padding-top: 15px;
  }
</style>
