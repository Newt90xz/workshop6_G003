<script setup>
// TODO: Utilizar 'defineProps' para declarar las propiedades que se recibirán desde el padre.
// Se espera recibir: asignaturas (Number) y promedio (Number)
</script>

<template>
  <div class="card">
    <header class="card-header">
      <p class="card-header-title">
        Estadísticas Académicas
      </p>
    </header>
    <div class="card-content">
      <div class="content">
        <ul>
          <!-- TODO: Reemplazar los valores '0' estáticos por las props correspondientes -->
          <li><strong>📚 Asignaturas Cursadas:</strong> 0</li>
          <li><strong>⭐ Promedio General:</strong> 0.0</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>
</style>
