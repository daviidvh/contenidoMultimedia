<template>
  <div class="video-section">
    <div class="contenido">
      <h2>Historia de Filomena</h2>
    <div class="texto">
      <p>
      La nevada Filomena, ocurrida en enero de 2021 en España, fue un fenómeno meteorológico
      extraordinario que dejó una profunda impresión en la memoria colectiva. Caracterizada por su intensidad y duración, 
      Filomena cubrió ciudades como Madrid con un manto blanco inusualmente espeso.
    </p>

    <p>
      Durante varios días, la capital española se sumió en un paisaje de ensueño, transformando sus calles y monumentos 
      emblemáticos en un cuadro invernal. Sin embargo, la belleza de la nevada también trajo consigo desafíos considerables, 
      afectando el tráfico, la movilidad y la rutina diaria de los ciudadanos.
    </p>
      <p>
      A pesar de las dificultades, la nevada Filomena también resaltó la solidaridad y la resiliencia de la comunidad.
      Vecinos se unieron para ayudarse mutuamente, creando historias de apoyo y generosidad en medio de la adversidad.
    </p>
    <p>
      En retrospectiva, la nevada Filomena se convierte en un capítulo memorable, 
      recordándonos la capacidad de la naturaleza para sorprendernos y la capacidad humana para adaptarnos y 
      encontrar belleza incluso en las situaciones más desafiantes.
    </p>
    </div>
    <div class="video-container">
      <video autoplay muted class="responsive-video">
        <source src="../video.mp4" type="video/mp4">
      </video>
    </div>
  </div>
</div>

</template>


<style scoped>
.video-section {
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

.video-container {
  width: 100%; 
  position: relative;
  padding-bottom: 56.25%;
  overflow: hidden;
  margin-top: 20px; 
}

.responsive-video {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

@media screen and (max-width: 768px) {
  .video-container {
    margin-top: 0; 
  }
}
</style>