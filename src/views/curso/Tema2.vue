<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Principios de la bioética'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    p(data-aos="fade-right") La bioética ha sido un campo de estudio interdisciplinario que combina la biología, la ética y las ciencias humanas, con el claro objetivo de asegurar la supervivencia de la humanidad y del planeta. 

    .row.mb-5
      .col-lg-7

        .bg-color-1.p-4(data-aos="fade-left").mb-4
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/1.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Los primeros indicios de pensamiento bioético se encuentran en textos antiguos, como el Juramento Hipocrático, que establece principios éticos en la práctica médica.

        p(data-aos="fade-left") En 1971, Potter se refirió a la bioética como el medio por el cual las personas podían sobrevivir, puesto que argumentaba que la supervivencia del futuro estaba en manos de esta disciplina, pues no solo regulaba la interacción entre personas, como lo hace la ética tradicional, sino que también abarcaba la relación entre las personas y los sistemas biológicos.

        p(data-aos="fade-left") Este enfoque ampliado, coloca a la bioética como un puente entre las ciencias biológicas y las humanidades, y otorga a los profesionales de la salud, un marco para tomar decisiones que trascienden el ámbito clínico para integrar cuestiones ecológicas, políticas y sociales (Núñez de Castro, 2017).

        p(data-aos="fade-left") A continuación, vamos a estudiar los 4 principios de la bioética.

      .col-lg-5
        figure
          img(src="@/assets/curso/tema2/2.png", data-aos="zoom-in")

    #t_2_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.1] El principio de autonomía

    p(data-aos="fade-left") El principio de autonomía se refiere a la capacidad de las personas para tomar decisiones informadas sobre su propia vida y bienestar, sin coerción externa. Beauchamp y Childress (2001) definieron la autonomía como el derecho de los individuos a gobernarse a sí mismos, un concepto que tiene relevancia en el ámbito de la bioética, dando trascendencia en lo que respecta a la toma de decisiones médicas.

    .row.align-items-center.mb-5
      .col-lg-5
        figure
          img(src="@/assets/curso/tema2/3.png", alt="").mb-4.mb-lg-0
      .col-lg-7

        AcordionA(tipo="b")
          .div(titulo="Ejemplo concreto")
            p En un hospital, un paciente con una enfermedad terminal tiene el derecho de rechazar tratamientos que prolonguen su vida, si considera que su calidad de vida será insuficiente. Este acto, fundamentado en la autonomía, respeta el deseo del paciente de controlar su propio destino, aunque pueda contradecir las recomendaciones médicas.

          .div(titulo="Retos actuales")
            p La autonomía se ve desafiada en el contexto de la globalización, por la disparidad en el acceso a la información y los servicios de salud. En muchos países, las personas no pueden ejercer plenamente su autonomía porque no tienen acceso a la información médica adecuada o viven bajo sistemas donde no se respetan sus derechos básicos.

        p(data-aos="fade-left") La intervención conservadora de algunos profesionales de la salud, puede limitar el ejercicio pleno de la autonomía, exigiendo la creación de sistemas más inclusivos y equitativos que garanticen el respeto por las decisiones informadas de los pacientes (Núñez de Castro, 2017).


    #t_2_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.2] El principio de beneficencia

    .row.align-items-center.mb-5
      .col-lg-7
        p(data-aos="fade-left") Este principio no solo se refiere a la obligación de no causar daño, sino a la de actuar en beneficio de otros. Los actos de beneficencia son aquellos que buscan promover el bienestar de las personas, protegiéndolas de daños y ayudándolas a alcanzar su máximo potencial. Este principio está presente en el código de conducta de la mayoría de las profesiones médicas y sociales.

        AcordionA(tipo="b")
          .div(titulo="Ejemplo concreto")
            p Un médico que prescribe un tratamiento preventivo para una población vulnerable, está cumpliendo con su deber de beneficencia. Otro ejemplo podría ser la organización de campañas de vacunación masiva en países en vías de desarrollo, lo que protege a la población de enfermedades prevenibles.

          .div(titulo="Retos actuales")
            p El reto de la beneficencia en un mundo globalizado, está relacionado con la equidad. #[strong ¿Cómo se puede garantizar el bien común cuando los recursos son limitados?] Las vacunas contra el COVID-19 han sido un claro ejemplo de cómo la distribución desigual de recursos, puede generar tensiones éticas. En muchas naciones ricas, se logró vacunar a un alto porcentaje de la población rápidamente, mientras que, en los países más pobres, la escasez de vacunas impidió que las personas vulnerables recibieran la protección necesaria, creando una desigualdad que desafía el principio de beneficencia a nivel global (Silveira Gorski & Méndez Baiges, 2015).

      .col-lg-5
        figure
          img(src="@/assets/curso/tema2/4.png", alt="").mt-4.mt-lg-0


    #t_2_3.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.3] El principio de no maleficencia

    p(data-aos="fade-left") El principio de no maleficencia puede ser resumido en la máxima hipocrática “primum non nocere” o "lo primero, no hacer daño". Este principio no se limita a evitar causar daño físico intencionado, sino que también se extiende a evitar el daño indirecto o involuntario a los pacientes y al entorno que les rodea. 
    .row.align-items-center.mb-5
      .col-lg-5
        figure
          img(src="@/assets/curso/tema2/5.png", alt="").mb-4.mb-lg-0
      .col-lg-7
        p(data-aos="fade-left") El profesional de la salud, tiene la obligación moral de garantizar que sus acciones, o la falta de ellas, no causen perjuicio.

        AcordionA(tipo="b")
          .div(titulo="Ejemplo concreto")
            p Un ejemplo clásico sería la decisión de un médico de no realizar una cirugía extremadamente arriesgada a un paciente frágil, dado que las probabilidades de éxito son mínimas y el procedimiento podría empeorar su estado de salud.

          .div(titulo="Retos actuales")
            p En el contexto de la bioética global, este principio se enfrenta a nuevos dilemas. Un caso relevante es el uso de tecnologías avanzadas en medicina que, aunque prometen curas milagrosas, pueden conllevar efectos secundarios complejos. Además, las decisiones políticas globales relacionadas con el cambio climático, también se pueden enmarcar bajo este principio. La emisión descontrolada de gases contaminantes, causa daño no solo a la humanidad presente, sino también a las futuras generaciones, y los líderes políticos y económicos tienen la responsabilidad de actuar conforme a este principio (Beauchamp & Childress, 2001).


    #t_2_4.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.4] El principio de justicia

    p(data-aos="fade-left") El principio de justicia se refiere a la distribución equitativa de los recursos, oportunidades y responsabilidades. En bioética, esto implica que todas las personas tienen derecho a un acceso justo a los tratamientos y servicios, independientemente de su origen étnico, clase social o capacidad económica.

    .row.align-items-start.mb-5
      .col-lg-7

        AcordionA(tipo="b")
          .div(titulo="Ejemplo concreto")
            p Un hospital que garantiza que todos sus pacientes, sin tener limitaciones por tipo de seguro médico, reciban el mismo nivel de atención, estaría aplicando el principio de justicia.

          .div(titulo="Retos actuales")
            p En un contexto global, las desigualdades en el acceso a los servicios de salud, representan un desafío constante para el principio de justicia. Mientras que en algunos países la atención médica es un derecho garantizado, en otros se limita a aquellos que pueden pagar por ella.

            p Además, la justicia se enfrenta a retos importantes en situaciones de crisis humanitarias, como la distribución de recursos limitados durante desastres naturales o pandemias. Estos dilemas plantean preguntas sobre cómo se deben asignar los recursos escasos para lograr un reparto justo entre las poblaciones más vulnerables (Pérez Toro, 2016).


      .col-lg-5
        figure
          img(src="@/assets/curso/tema2/6.png", alt="").mt-4.mt-lg-0

    p(data-aos="fade-left") Es así como los principios de autonomía, no maleficencia, beneficencia y justicia, forman la base de la bioética contemporánea, especialmente en un mundo globalizado. 

    p(data-aos="fade-left").mb-5 Cada principio ofrece una guía para enfrentar los dilemas éticos actuales, desde la atención médica individual hasta las decisiones globales sobre la distribución de recursos es por esto que los profesionales de hoy no solo deben ser conscientes de estos principios, sino también deben aplicarlos con sensibilidad y flexibilidad en un contexto en constante cambio. Las decisiones bioéticas que toman no solo afectan a los individuos directamente involucrados, sino también a la sociedad y al medio ambiente en su conjunto. 

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10
        .bg-color-1.p-4(data-aos="fade-left")
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/7.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Cada uno de estos enfoques ofrece una estructura adaptable a distintos tipos de conflicto y niveles de formalidad, permitiendo a las partes optar por el método más adecuado, según sus necesidades y la naturaleza del desacuerdo. Conozcamos más sobre cada uno de ellos.


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
  name: 'Tema2',
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

<style lang="sass"></style>
