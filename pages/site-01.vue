<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        Site 01
      </h1>
      <p class="parrafo">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda, eveniet.
      </p>
      <div class="links">
        <a
          href="/"
          rel="noopener noreferrer"
          class="button--green"
        >
          Home
        </a>
        <a
          href="https://bonitomexico.com/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Bonito Mexico Store
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
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.parrafo {
  font-weight: 300;
  font-size: 30px;
  color: #0c0c0c;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
