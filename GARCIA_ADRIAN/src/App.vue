<script setup>
// TODO: Importar los componentes PerfilEstudiante y Estadisticas
// import ...

// TODO: Importar 'ref' y 'onMounted' de 'vue'
// import { ref, onMounted } from 'vue'

// TODO: Crear un estado reactivo llamado 'datosEstudiante' con un objeto vacío usando 'ref'
// const datosEstudiante = ...

// TODO: Utilizar el hook 'onMounted' para simular la carga de datos.
// Dentro del hook, utilizar setTimeout de 2 segundos para asignar al objeto
// 'datosEstudiante.value' los siguientes datos ficticios:
// - nombre: 'Juan Pérez'
// - carrera: 'Ingeniería Civil Informática'
// - asignaturas: 40
// - promedio: 5.8

// TODO (Punto de Bonificación): Crear una función que escuche el evento 'actualizar-semestre'
// y aumente en 1 la cantidad de asignaturas cursadas.
</script>

<template>
  <div class="container is-max-desktop mt-6">
    <div class="box">
      <h1 class="title has-text-centered is-3">Dashboard del Estudiante</h1>
      <hr>

      <div class="columns is-multiline">
        <div class="column is-full">
          <!-- TODO: Renderizar el componente PerfilEstudiante aquí -->
          <!-- TODO: Pasar las props necesarias usando v-bind (:) -->
          <!-- TODO (Bonificación): Escuchar el evento @actualizar-semestre -->
          <div class="notification is-warning has-text-centered">
            Renderizar <code>&lt;PerfilEstudiante /&gt;</code> aquí
          </div>
        </div>

        <div class="column is-full">
          <!-- TODO: Renderizar el componente Estadisticas aquí -->
          <!-- TODO: Pasar las props necesarias usando v-bind (:) -->
          <div class="notification is-info has-text-centered">
            Renderizar <code>&lt;Estadisticas /&gt;</code> aquí
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* No necesitas escribir estilos adicionales si usas Bulma, 
   pero puedes agregar retoques aquí si lo deseas. */
</style>
