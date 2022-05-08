<template>
  <div class="equipo">
    <p>Escudo</p>
    <p>{{ puntos }}</p>
    <button
        type="button"
        class="text-white bg-blue-500 hover:bg-blue-700 focus:ring-blue-200 font-medium rounded-lg px-4 py-2.5 mr-2 mb-2 focus:outline-none"
        @click="plus">+</button>
    <button
        type="button"
        class="text-white bg-blue-500 hover:bg-blue-700 focus:ring-blue-200 font-medium rounded-lg px-4 py-2.5 mr-2 mb-2 focus:outline-none"
        @click="minus">-</button>
  </div>
</template>

<script>
export default {
  name: 'EquipoDeporte',

  data() {
    return {
      puntos: 0
    }
  },
  methods: {
    minus() {
      this.puntos = Math.max(this.puntos - 1, 0)
    },
    plus() {
      this.puntos++
    }
  },
}
</script>
