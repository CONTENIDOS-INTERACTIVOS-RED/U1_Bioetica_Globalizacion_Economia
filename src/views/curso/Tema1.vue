<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Introducción a la bioética en un contexto global'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-7
        p(data-aos="fade-right") La bioética ha evolucionado como una disciplina multidimensional que combina ciencias, humanidades y principios éticos, ofreciendo respuestas a los dilemas que emergen en un mundo globalizado. En este contexto, el PDF La bioética en un contexto global, explora cómo la bioética se ha consolidado como un puente entre culturas y disciplinas, enfrentando desafíos éticos relacionados con la salud, la sostenibilidad y los derechos humanos. A través de un recorrido histórico que abarca desde los fundamentos del Juramento Hipocrático hasta los marcos éticos globales contemporáneos, se destaca su relevancia para los profesionales de hoy, quienes, independientemente de su campo, deben tomar decisiones que impactan profundamente en la vida humana y el medio ambiente. Este material busca proporcionar las bases necesarias para reflexionar sobre la importancia de la bioética en la construcción de un futuro más justo y sostenible.

        a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
          .anexo__icono(:style="{'background-color': '#FCDFDB'}")
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p <strong>Anexo. </strong> La bioética en un contexto global

      .col-lg-5
        figure
          img(src="@/assets/curso/tema1/1.png", data-aos="zoom-in").mt-4.mt-lg-0

    p(data-aos="fade-right") La historia y la evolución de la bioética, se pueden resumir en varios hitos claves:

    .PurpleContainer.pt-5
      .row.justify-content-center.align-items-center
        .col-lg-8
          h2.text-center.mb-5(data-aos="fade-right") La historia y la evolución de la bioética

          ImagenInfografica.color-secundario.mb-5
            template(v-slot:imagen)
              figure
                img(src='@/assets/curso/infografias/1.png', alt='', style="max-width: 583px;").mx-auto

            .bg-color-3.p-3(x="50%" y="5%" numero="+")
              h5 Orígenes filosóficos
              p La bioética tiene raíces en la filosofía, la teología y el derecho. Estas disciplinas comenzaron a encarar cuestiones éticas relacionadas con la vida y la salud, estableciendo un marco para la discusión sobre la moralidad en la medicina y la investigación.

            .bg-color-3.p-3(x="79.5%" y="27.5%" numero="+")
              h5 Informe Belmont (1979)
              p Este informe fue relacionado con la formalización de principios bioéticos en la investigación con seres humanos. Estableció criterios generales que guiarían la ética en la investigación, enfatizando la importancia de la justicia, la beneficencia, y el respeto por las personas.
            
            .bg-color-3.p-3(x="79.5%" y="72.5%" numero="+")
              h5 Principios de bioética
              p En 1979, Tom L. Beauchamp y James F. Childress publicaron "Principles of Biomedical Ethics", que se convirtió en un texto representativo en el campo. Este trabajo introdujo el "principalísimo", que se centra en cuatro principios éticos: autonomía, beneficencia, no maleficencia y justicia, y ha sido ampliamente adoptado por profesionales de la salud y comités de ética.

            .bg-color-3.p-3(x="50%" y="95%" numero="+")
              h5 Bioética global
              p Van Rensselaer Potter, en 1971, propuso la bioética como una disciplina que integra biología, ecología, medicina y valores humanos. Su enfoque enfatizaba la necesidad de considerar las implicaciones éticas de la investigación científica, en el contexto del medio ambiente, lo que llevó a la noción de "bioética global".

            .bg-color-3.p-3(x="20%" y="72.5%" numero="+")
              h5 Desarrollo de comités de ética
              p A partir de los años 80, se establecieron comités de ética en hospitales y organizaciones de investigación, para evaluar proyectos y prácticas en salud, asegurando que se cumplieran los principios bioéticos en la atención médica y la investigación.

            .bg-color-3.p-3(x="20.2%" y="27.5%" numero="+")
              h5 Diversidad de enfoques
              p La bioética ha evolucionado para incluir diversas perspectivas, como la bioética secular y la bioética moral, reflejando la pluralidad de valores y creencias, en sociedades democráticas y multiculturales.

    .SplitContainer2.mb-5
      .row.justify-content-center  
        .col-lg-9
          .bg-color-1.shadow-soft.py-4.px-lg-5(data-aos="fade-up")
            p(data-aos="fade-right").mb-0 En resumen, la bioética ha pasado de ser un campo emergente en la filosofía y la ética médica, para convertirse en una disciplina integral que aborda los desafíos éticos contemporáneos en la medicina y la investigación, adaptándose a los cambios sociales y tecnológicos, a lo largo del tiempo. 


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
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.tabs-content
  background-color: $color-sistema-h
.img-infografica
  background-color: $color-adicional-1

.SplitContainer
  background: rgb(85,122,250)
  background: linear-gradient(0deg, rgba(232,238,253,1) 0%, rgba(232,238,253,1) 50%, rgba(255,255,255,1) 50%)

  .yellowCard
    padding: 2rem
    background-color: #FBF6DB

.PurpleContainer
  background-color: rgb(255,253,246)

.SplitContainer2
  background: rgb(85,122,250)
  background: linear-gradient(0deg, rgba(255,255,255,1) 0%, rgba(255,255,255,1) 50%, rgba(255,253,246,1) 50%)

  .yellowCard
    padding: 2rem
    background-color: #FBF6DB
</style>
