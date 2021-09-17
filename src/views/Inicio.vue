<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.svg')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0.text-white Emprendimiento digital
          
          .h2.text-white Información del programa
          .banner-principal__datos
            ul.text-white
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Emprendimiento digital
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 62360013
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Total: 
                p.banner-principal__datos__item__texto 48 Horas
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Duración: 
                p.banner-principal__datos__item__texto 1 mes
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo 
                .banner-principal__datos__item__texto
              

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe width="560" height="315" src="https://www.youtube.com/embed/1VhhBnNLpi0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>                            

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p.mb-3 ¡Bienvenido! 
    p ¿Quién recuerda haber usado una máquina de escribir para hacer una carta? O, ¿quién hizo un volante a mano para la publicidad de un evento o negocio?, para esto quizá tuvieron que buscar el término emprendimiento en una enciclopedia en el tomo que incluía la letra #[strong e]. Pero hoy es tan fácil como usar el asistente de voz del teléfono y decirle: “Emprendimiento concepto”, o tal vez “Tendencia de ventas en Colombia este año” y la información estará en el teléfono en pocos segundos, o tan sencillo como encontrar aplicaciones móviles que permiten diseñar, de manera intuitiva y sin ser un experto, un banner para redes sociales o un volante para ser enviado por sistemas de mensajería instantánea, entre otros. 

    p El mundo está cambiando y la tecnología llegó para quedarse, transformar la sociedad y, por supuesto, al emprendimiento. Actualmente hay muchas empresas que han surgido con ayuda de las herramientas digitales posicionándose a nivel mundial como Airbnb, Amazon o, en Colombia, Rappi que tuvieron la certeza de que el emprendimiento y la tecnología van de la mano y que es fundamental prepararse para esta revolución tecnológica.

    p El Servicio Nacional de Aprendizaje SENA, la entidad más querida por los colombianos, conoce la realidad del país y las necesidades que tienen los colombianos hoy para emprender y desarrollar poderosas ideas de negocio, apalancadas por las herramientas tecnológicas; por eso, le da la bienvenida a este programa denominado #[strong Emprendimiento digital], donde encontrará una ayuda fundamental para aprender sobre emprendimiento y herramientas digitales que permitan potenciar ideas de negocio. 

    p Se abordarán aspectos importantes del emprendimiento y del emprendedor, sus características, el contexto, las herramientas tecnológicas que han llegado con la cuarta revolución industrial, redes sociales, pero también la integración de estas herramientas dentro de una idea de negocio y la forma de presentarla de manera efectiva.

    p.mb-0 Le invitamos a disfrutar de cada momento del programa y que sea protagonista de este proceso formativo, así como el protagonista de su propio emprendimiento, le invitamos a vivir este momento y transformarse en emprendedores digitales, nuevamente: ¡bienvenido! 


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p Desde la década de los años noventa, el emprendimiento ha demostrado ser un poderoso fenómeno capaz de cambiar las dinámicas económicas globales y los estilos de vida de las sociedades; así, las grandes empresas, con estructuras rígidas y producciones en serie, abrieron paso a pequeñas empresas con estructuras flexibles que ofrecen bienes y servicios con un alto componente innovador, cambiando de este modo las reglas del juego en las economías del mundo. 

    p Colombia no ha estado al margen de ese fenómeno, pues ha reconocido al emprendimiento como un vehículo en la generación del crecimiento económico a través de la cohesión social, la renovación económica, el desarrollo regional, el aumento de la productividad y la competitividad, entre otros factores.
    
    p Por eso es necesario que los emprendimientos sean globales y que usen herramientas digitales como punto de apoyo para un negocio generando un concepto de emprendimiento digital, es decir, que desarrollen una estrategia digital como pilar de su modelo de negocio. 

    p.mb-0 El SENA conocedor de estas necesidades, ofrece el programa complementario #[strong Emprendimiento digital] para brindar a la población interesada herramientas que conlleven a la estructuración de estrategias digitales para la estructuración de sus ideas de negocio, apoyados en herramientas TIC, Big data, marketing digital, entre otras, fortaleciendo en el emprendedor las competencias tecnológicas digitales y generando valor agregado acorde con las nuevas necesidades del mercado global, nacional y local.
 

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a<br> desarrollar

    ul.lista-ul
      li 
        i.lista-ul__vineta
        | Fomentar cultura emprendedora según habilidades y competencias personales.     
      
  
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de <br> ingreso

    ul.lista-ul
      li 
        i.lista-ul__vineta
        | Bachilleres, técnicos, tecnólogos o profesionales de cualquier núcleo básico de conocimiento.    


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Estrategia metodológica

    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en la utilización de las tecnologías de la información y la comunicación, integradas en ambientes virtuales de aprendizaje que, en todo, caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 

    p Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje que se logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
   

    p.p1 - El instructor – Tutor
    p.p1 - El entorno
    p.p1 - Las TIC
    p.p1 - El trabajo colaborativo    


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 7. Creditos
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
