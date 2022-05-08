<template>
  <div class="marcador flex">
    <EquipoDeporte class="flex-1 w-32" />
    <EquipoDeporte class="flex-1 w-32" />
  </div>
</template>

<script>

import EquipoDeporte from './Equipo.vue'

export default {
  name: 'PanelMarcador',
  components: {
    EquipoDeporte,
  },
}
</script>
