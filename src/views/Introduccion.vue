<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.bg-c1
      .col-12
        .px-5.pt-5
          p.mb-5(data-aos="fade-right") Para iniciar el desarrollo temático y conceptual de este componente formativo, es importante tener un contexto sobre lo que se tratará en este; por tal motivo, a continuación, se presenta una breve introducción, que orientará este aprendizaje:
          figure(data-aos="fade-left")
            .video
              iframe(width="560" height="315" src="https://www.youtube.com/embed/6xXC7zcZNls" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
