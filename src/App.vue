<template>
  <div id="app">
    <div class="container">
      <Repository />
    </div>
  </div>
</template>

<script>
import Repository from './components/Repository'

export default {
  name: 'app',
  components: {
    Repository
  }
}
</script>

<style>
body {
  font-family: 'Roboto', sans-serif;
  line-height: 1.6;
}
/* .container {
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
} */
</style>
