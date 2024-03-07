<template>
    <div class="imagen-section">
      <div class="contenido">
        <h2>Imagen de Filomena</h2>
        <div class="texto">
          <p>Descripción de la imagen</p>
          <p>
            La imagen captura la majestuosidad de la Fuente de Cibeles en Madrid, España, durante el 
            fenómeno meteorológico conocido como Filomena. La escena muestra a la diosa Cibeles, icónica y 
            majestuosa en su carro tirado por leones, envuelta en un manto de nieve que transforma la escenografía 
            urbana en un paisaje invernal sorprendente. La combinación de la fuerza arquitectónica de la fuente y la 
            inusual capa de nieve refleja la dualidad entre lo clásico y lo efímero, creando una imagen cautivadora que 
            fusiona la historia y la naturaleza en un momento único.</p>
        </div>
      <div class="imagen-container">
        <img src="../imagen.jpg" alt="Imagen de Filomena" class="responsive-imagen">
      </div>
    </div>
</div>

  </template>
  
  <script setup>

</script>
  
  <style scoped>
  .imagen-section {
    display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  align-items: flex-start; 
  }
  
  .contenido {
    display: grid;
  width: 100%;
  max-width: 800px; 
  border: 2px solid #dddddd56;
  padding: 20px; 
  box-sizing: border-box; 
  }
  
  .texto {
    width: 100%;
  }
  
  .imagen-container {
    width: 100%;
    position: relative;
    overflow: hidden;
    margin-top: 20px;
  }
  
  .responsive-imagen {
    width: 100%;
    height: auto;
    max-width: 100%; 
    max-height: 100vh; 
  }
  
  @media screen and (max-width: 768px) {
    .imagen-container {
      margin-top: 0;
    }
  }
  </style>