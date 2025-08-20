<template>
    <div class="p-4 border rounded-lg bg-gray-100 text-center">
      <h2 class="text-xl font-bold text-green-600">¡Hola desde Vue! 🎉</h2>
      <p>Contador: {{ count }}</p>
      <button 
        @click="count++" 
        class="mt-2 px-3 py-1 bg-green-500 text-white rounded hover:bg-green-600"
      >
        Sumar
      </button>
    </div>
  </template>
  
  <script setup>
  import { ref } from 'vue'
  
  const count = ref(0)
  </script>
  
  <style scoped>
  /* Estilos locales opcionales */
  </style>
  