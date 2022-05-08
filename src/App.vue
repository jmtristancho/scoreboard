<template>
  <ListaEscudos />
  <PanelMarcador />
  <RelojTiempo />
</template>

<script>
import ListaEscudos from './components/Escudos.vue'
import PanelMarcador from './components/Marcador.vue'
import RelojTiempo from './components/Reloj.vue'

export default {
  name: 'App',
  components: {
    ListaEscudos,
    PanelMarcador,
    RelojTiempo,
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
