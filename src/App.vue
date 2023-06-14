<template>
  <div id="app">
    <ACard>
      <h2 slot="header">My Card <strong>Header</strong></h2>
      Aquí va contenido
    </ACard>
    <ACard>
      Aquí va contenido
    </ACard>
  </div>
</template>

<script>
import ACard from './components/ACard.vue'

export default {
  name: 'App',
  components: {
    ACard
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
