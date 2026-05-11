<script setup>
// TODO: Utilizar 'defineProps' para declarar las propiedades que se recibirán desde el padre.
// Se espera recibir: nombre (String) y carrera (String)
</script>

<template>
  <div class="card">
    <div class="card-content">
      <div class="media">
        <div class="media-left">
          <figure class="image is-48x48">
            <!-- Icono de perfil por defecto -->
            <img src="https://bulma.io/assets/images/placeholders/96x96.png" alt="Profile" />
          </figure>
        </div>
        <div class="media-content">
          <!-- TODO: Reemplazar 'Nombre por defecto' con la interpolación de la prop correspondiente -->
          <p class="title is-4">👤 Nombre por defecto</p>
          <!-- TODO: Reemplazar 'Carrera por defecto' con la interpolación de la prop correspondiente -->
          <p class="subtitle is-6">🎓 Carrera por defecto</p>
        </div>
      </div>
      
      <!-- TODO (Punto de Bonificación): Botón para Emitir Evento -->
      <!-- Agregar un @click que emita un evento llamado 'actualizar-semestre' hacia el padre -->
      <div class="content mt-4">
        <button class="button is-primary is-small">
          Actualizar Semestre (+1 Asignatura)
        </button>
      </div>
    </div>
  </div>
</template>

<style scoped>
</style>
