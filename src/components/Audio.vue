<template>
    <div class="audio-section">
      <h2>Audio de Filomena</h2>
      <audio controls autoplay>
        <source src="../audio.mp3" type="audio/mp3">
        Tu navegador no soporta el elemento de audio.
      </audio>
    </div>
  </template>
  
  <script setup>
  </script>
  
  <style scoped>
  .audio-section {
    max-width: 800px;
    margin: 20px auto;
    text-align: center;
  }
  
  h2 {
    font-size: 1.5rem;
    margin-bottom: 10px;
  }
  </style>
  