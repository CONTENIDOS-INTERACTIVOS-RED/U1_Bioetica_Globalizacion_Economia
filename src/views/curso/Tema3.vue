<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Impacto de la globalización en los dilemas éticos contemporáneos'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .row.mb-5
      .col-lg-7
        p(data-aos="fade-right") La globalización, como fenómeno transformador, ha incrementado la interdependencia económica, política y social entre las naciones, redefiniendo las dinámicas éticas a nivel mundial. A continuación, en el PDF Impacto de la globalización en los dilemas éticos contemporáneos, se examina cómo la interacción global plantea nuevos dilemas éticos en áreas clave como la salud, los derechos humanos y el medio ambiente, exigiendo una reconfiguración de los principios bioéticos tradicionales. A través de ejemplos concretos y análisis crítico, se invita al lector a reflexionar sobre los desafíos éticos que emergen en un mundo interconectado, destacando la importancia de la bioética como disciplina esencial para promover la justicia, la equidad y la sostenibilidad en un contexto globalizado.

        a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_2.pdf')" target="_blank")(data-aos="flip-up")
          .anexo__icono(:style="{'background-color': '#FCDFDB'}")
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p <strong>Anexo. </strong> Impacto de la globalización en los dilemas éticos contemporáneos 

      .col-lg-5
        figure
          img(src="@/assets/curso/tema3/1.png", data-aos="zoom-in").mt-4.mt-lg-0


    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            // Referencias agregadas según formato solicitado
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/51423" target="_blank" rel="noopener noreferrer") García Peregrín, E. (2018). Bioética: temas para el debate. Vol. 2. Bubok Publishing S.L.
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/41139" target="_blank" rel="noopener noreferrer") Garza Grimaldo, J. G. & Valqui Cachi, C. (2017). Los valores en la dialéctica de la humanidad y la naturaleza en el siglo XXI. Ediciones y Gráficos Eón.
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/40950" target="_blank" rel="noopener noreferrer") Núñez de Castro, I. (2017). La bioética: un camino para el presente. ITESO - Instituto Tecnológico y de Estudios Superiores de Occidente.
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/56380" target="_blank" rel="noopener noreferrer") Silveira Gorski, H. C., & Méndez Baiges, V. (2015). Bioética y derecho. Editorial UOC.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=KhvDUJMQtXQ" target="_blank" rel="noopener noreferrer") Universidad del Rosario. (2024, March 22). Por qué los latinoamericanos están migrando como nunca antes [Video]. YouTube.
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=gUSdUvpLTzQ" target="_blank" rel="noopener noreferrer") Pastoral Social e Innovación - Madrid. (2023, June 25). JMMR 2023 (2). Causas de la migración forzada. Jornada Mundial del Migrante y del Refugiado. [Video]. YouTube.
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=0uC7BdOV0ew" target="_blank" rel="noopener noreferrer") RevistaMSP. (2022, May 28). #EspecialMSP | Contaminación ambiental de la industria de la moda [Video]. YouTube.
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=sIQnED7PM-Y" target="_blank" rel="noopener noreferrer") GRAINvideo. (2020b, March 31). ¿Qué tiene que ver la producción industrial de carne con la crisis climática? [Video]. YouTube.


         

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')
</template>

<script>
import BannerInterno from '../../components/plantilla/BannerInterno'
export default {
  name: 'Tema3',
  components: {
    BannerInterno,
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>
