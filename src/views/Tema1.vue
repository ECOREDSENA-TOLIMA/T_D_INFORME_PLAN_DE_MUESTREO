<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Presentación    

    .row
      .col-xl-12
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2.my-5 1.1 Definición
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5
        figure
          img(src='@/assets/curso/temas/tema1/img1.jpg').m-auto
      .col-lg-7
        p  El plan de muestreo es un instrumento de planeación en el cual se definen los parámetros sobre el muestreo que se desea realizar . Un plan de muestreo debe incluir elementos específicos acerca de lugares o sitios de muestreo, métodos y técnicas, número de muestras, clases de muestras, incluidas: volumen del agua, filtrada o entera, preservativos y tiempos de retención, número y clases de muestras de garantía de calidad/control de calidad (GA/CC).
        .cajon.color-primario.p-3.mb-3
          p.mb-0 Los planes de muestreo ayudan a garantizar que los resultados no tengan errores y cumplan los objetivos del proyecto o programa de calidad del agua.
        p En general se recomienda que el plan de muestreo especifique como mínimo los siguientes ítems según la ICONTEC (2006), en la Norma Técnica Colombiana NTC 5667-1, Directrices para el diseño de programas de muestreo.
    Separador
    .row
      .col-xl-12
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2.my-5 1.2 Elementos del plan de muestreo
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10.col-md-4.mb-4.mb-md-0(data-aos="flip-left")
        .titulo-sexto.color-acento-contenido.offset-0
          h5 Figura 1.
          span  #[i  Elementos del plan de muestreo]
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10.desktop(data-aos="flip-up")
        figure
          img(src='@/assets/curso/temas/tema1/img2.svg', alt='En la figura 1 se muestran los diferentes elementos que hacen referencia al plan de muestreo entre los que se tienen: el objetivo, el sitio de toma de muestra, el método o técnica, los parámetros, los formatos, los elementos de seguridad, el personal y los instrumentos.')
      .col-lg-12.movil
        figure
          img(src='@/assets/curso/temas/tema1/img2_1.svg', alt='En la figura 1 se muestran los diferentes elementos que hacen referencia al plan de muestreo entre los que se tienen: el objetivo, el sitio de toma de muestra, el método o técnica, los parámetros, los formatos, los elementos de seguridad, el personal y los instrumentos.')
    Separador
    .row
      .col-xl-12
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2.my-5 1.3 Pasos para elaborar la práctica
  
    .tarjeta.p-5(titulo="Ejemplo - 1")
      .row.justify-content-center
        .col-lg-10.desktop
          ImagenInfograficaB.color-acento-botones
            template(v-slot:imagen)
              figure
                img(src='@/assets/curso/temas/tema1/img3.svg', alt='')

            div(x="33%" y="18.5%" tooltip="Ver más" numero="+")
              .tarjeta.white-card.p-4
                .row
                  .col-lg-12
                    .h4 Objetivo
                    p.mb-3 Señala la finalidad del muestreo o actividad específica. En la redacción puede proponerse un solo objetivo general o bien, en ocasiones, desglosar diferentes niveles de éste a través de objetivos específicos.
            div(x="58%" y="8.5%" tooltip="Ver más" numero="+")
              .tarjeta.white-card.p-4
                .row
                  .col-lg-12
                    .h4 El sitio de la muestra y puntos de muestreo
                    p.mb-3 Definir el sitio donde se realizará la muestra y revisar el contexto histórico del mismo, en cuanto a los puntos de muestreo se deben considerar para cada caso particular de monitoreo, dependiendo de los objetivos propuestos. Estos puntos de toma de muestra deben responder a una decisión estratégica que contemple los alcances del proyecto, los vacíos de información y la necesidad de conocimientos para la gestión del recurso hídrico. De esta forma, se generará una base de datos con las concentraciones de elementos de interés, que describan la situación del lugar donde se realizó la toma de muestra. Es importante definir qué efecto se quiere medir para poder ubicar los puntos de muestreo de manera consistente. La ubicación de los puntos va a sentar las bases para el correcto análisis de los datos generados de calidad de agua y sus limitaciones.
            div(x="68%" y="18%" tooltip="Ver más" numero="+")
              .tarjeta.white-card.p-4
                .row
                  .col-lg-12
                    .h4 El método y técnica para usar
                    p.mb-3 Establecer que método de muestreo es aplicable y que técnica se puede utilizar, estos dos elementos brindaran información referente a la frecuencia y duración del muestreo. 
                    p.mb-3 La duración de los muestreos va a depender de las diferentes variables de peso y de los objetivos que se consideren necesarios. En el caso de un monitoreo, es deseable que la duración de los muestreos sea a largo plazo para mantener constante en el tiempo, la recolección de información, consolidando el entendimiento temporal de la calidad de agua. Se busca así una generación continua de herramientas para la toma de decisiones, promoviendo buenas prácticas de desarrollo sustentable que no afecten al recurso hídrico.
                    p.mb-3 La frecuencia de la toma de muestras va a depender del peso de las variables de calidad de agua que estemos analizando, sus características particulares y su relación con la variabilidad ambiental. A su vez, los objetivos específicos del monitoreo juegan un rol de importancia en la definición de la frecuencia. Si el ambiente presenta cambios en el tiempo (por ejemplo: sistemas de ríos en cuestión de minutos u horas y lagos en cuestión de días o semanas), el patrón temporal de muestreo es de gran importancia. El plan de muestreo deberá tener en cuenta la resolución temporal prevista de los cambios en el ambiente.
            div(x="79%" y="50%" tooltip="Ver más" numero="+")
              .tarjeta.white-card.p-4
                .row
                  .col-lg-12
                    .h4 Los parámetros para medir
                    p.mb-3 Es muy importante prestar atención a las variables que se vinculan a las problemáticas a las cuales se les quiere dar solución con el plan de muestreo. La definición de los parámetros a analizar es una de las variables de mayor peso a la hora de calcular el costo beneficio. Los análisis químicos se encuentran dentro de las variables más costosas sin embargo por eso que su importancia no es menor. Estas definiciones pueden ser conducidas con mayor facilidad cuando se cuenta con bibliografía o datos previos que ayuden definir los parámetros.
                    p.mb-3 Es importante definir los alcances del muestreo en relación con los parámetros que se tomarán en cuenta. Es significativo contar con los valores guía recomendados para el uso del recurso analizado. En el caso de un relevamiento de calidad de agua ambiental se puede aplicar niveles guía de Protección de la Biota Acuática. Sin embargo, si se está analizando calidad de agua para recreación, por ejemplo, se debe considerar los valores guía definidos para este uso. A su vez, existe la posibilidad de monitoreos sobre el vertido de efluentes líquidos a cuerpos receptores. En ese caso se seguirán los estándares provinciales en cuanto a los parámetros de medición y los niveles máximos permitidos de descarga, facilitando la definición dentro del espectro de parámetros generales.

            div(x="68.5%" y="81.5%" tooltip="Ver más" numero="+")
              .tarjeta.white-card.p-4
                .row
                  .col-lg-12
                    .h4 Los instrumentos y equipos requeridos
                    p.mb-3 Dentro de esta parte se debe garantizar hacer un alistamiento previo de los elementos que serán requeridos para ello se debe establecer todos los insumos necesarios para la recolección de muestras, los cuales parten de la base de lo que se va a analizar y de las especificaciones del laboratorio al cual se remitirán las muestras colectadas. De esta forma se tendrá definido según lo que se vamos a medir, la naturaleza de los recipientes a emplear (botellas, frascos, tubos), la cantidad de recipientes en función de los puntos de muestreo, los equipos necesarios para la obtención de la muestra de agua (sogas, baldes, botellas Van Dorn, según corresponda) y los insumos para acondicionamiento y transporte de las muestras tales como conservadoras, refrigerantes, gradillas y reactivos, entre otros. Es aconsejable llevar dos repuestos de cada recipiente por cualquier eventualidad. Además de los insumos para la toma de muestras son importantes los materiales necesarios para el correcto etiquetado e identificación de las muestras.
                    p.mb-3 La preparación de rótulos se recomienda efectuarla previamente al momento del muestreo para optimizar los tiempos en el terreno. Las planillas de recolección de datos son parte importante de la preparación previa de materiales. Una planilla correctamente confeccionada que contenga un check-list (punteo o listado de todo lo necesario para cada punto de muestreo) es fundamental para estandarizar el control de la toma de muestras y, a su vez, funciona como un back-up (copia de seguridad) de la información generada en terreno.
                    p.mb-3 Todos los equipos que se utilicen en la implementación del monitoreo deben ser revisados y calibrados en el caso que corresponda, previos a la salida, para poder contar con los equipos en su correcto estado operativo. Para la recolección de datos in situ (temperatura, oxígeno disuelto, pH, conductividad eléctrica, sólidos totales disueltos o STD, potencial de óxido reducción u ORP, turbidez, salinidad) se recomienda utilizar equipos multiparamétricos robustos que soporten ser manipulados intensivamente en campo, describa dentro del plan de muestreo los equipos a utilizar y su calibración si es posible incluya el manual del equipo. 

            div(x="42.5%" y="91.05%" tooltip="Ver más" numero="+")
              .tarjeta.white-card.p-4
                .row
                  .col-lg-12
                    .h4 El personal y las competencias que debe manejar
                    p.mb-3 Establecer en el muestreo los perfiles o capacitaciones que debe tener el personal a realizar el muestreo de manera previa, la gran mayoría de los errores presentados o de las muestras que no pueden ser analizadas son por efecto de una mala manipulación o la ejecución de un mal procedimiento.
            
            div(x="32.5%" y="82.05%" tooltip="Ver más" numero="+")
              .tarjeta.white-card.p-4
                .row
                  .col-lg-12
                    .h4 Los elementos de seguridad y salud en el trabajo
                    p.mb-3 Debe dejarse por escrito los elementos de protección personal que deben ser llevados el día de la toma de muestra, al igual que como es su uso correcto.
            
            div(x="22.5%" y="51.5%" tooltip="Ver más" numero="+")
              .tarjeta.white-card.p-4
                .row
                  .col-lg-12
                    .h4 Los formatos requeridos para el registro de información
                    p.mb-3 Establecer todos los formatos que serán usados durante la puesta en marcha del muestreo, en este caso el plan de muestreo debe establecer: que fichas de seguridad y hojas de seguridad son requeridas, los rótulos y etiquetas a usar, la bitácora de campo o formato de registro de datos, y los demás formatos que garantices la cadena de custodia.
        .col-lg-12.movil
          a.anexo.mb-4(:href="obtenerLink('/downloads/anexo1.pdf')" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-pdf.svg")
            .anexo__texto
              p Descargar. Infografía - Pasos para elaborar la práctica
    Separador
    .row
      .col-xl-12
    #t_1_4.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2.my-5 1.4 Pasos para realizar el plan de muestreo

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-2.col-md-6.col-sm-4
        figure
          img(src='@/assets/curso/temas/tema1/img4.svg', alt='Imagen decorativa')
      .col-lg-8
        ol.lista-ol--cuadro
          li
          .lista-ol--cuadro__vineta
            span 1
          | Lea con anticipación sobre el objetivo y lugar de muestreo.
          li
          .lista-ol--cuadro__vineta
            span 2
          | Lea los elementos que debe contener el plan de muestreo.
          li
          .lista-ol--cuadro__vineta
            span 3
          | Inicie el proceso de redacción de cada elemento requerido para su caso específico.
          li
          .lista-ol--cuadro__vineta
            span 4
          | Apoye con imágenes el plan.
          li          
          .lista-ol--cuadro__vineta
            span 5
          | Recuerde dejar los formatos requeridos en formato PDF para que no sean modificables e incluir espacios como firmas y registro de fecha.


  
    Separador
    .row
      .col-xl-12
    #t_1_5.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2.my-5 1.5 Recomendaciones de diseño para elaborar el plan de muestreo

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image':`url(${require('@/assets/curso/temas/tema1/img5.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4        
        ul.lista-ul
          li
            i.fas.fa-angle-right
            | Abrir un archivo en Word. 
        br
        ul.lista-ul
          li
            i.fas.fa-angle-right
            | Registrar o desarrollar una portada para identificar el plan de muestreo.            
        br
        ul.lista-ul
          li
            i.fas.fa-angle-right
            | Desarrollar cada elemento puede usar imágenes, grafico o flujogramas.
        br
        ul.lista-ul
          li
            i.fas.fa-angle-right
            | Enumerar los anexos y mencionarlos dentro del texto para saber su necesidad en el documento.
        br
        ul.lista-ul
          li
            i.fas.fa-angle-right
            | Las recomendaciones deben apuntar a obtener mejores resultados o a optimizar la metodología. 
        

    Separador
    .row
      .col-xl-12
    #t_1_6.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2.my-5 1.6 Referentes Bibliográficos
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12 
        a.anexo.mb-4.mb-lg-0(href="https://www.fao.org/3/ah833s/Ah833s13.htm" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            p Food and agricultura organization. (s. f). Diseño de protocolos de muestreo.
        
        a.anexo.mb-4.mb-lg-0(href="https://www.emcali.com.co/documents/148832/183512/NTC+ISO+5667+-1+1995.pdf/c299f60c-2aed-b4d0-35da-81ddbae286b9?t=1532940931582&download=true" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            p Instituto Colombiano de Normas Técnicas y Certificaciones ICONTEC. (2006). Norma técnica Colombiana NTC-ISO 5667-1 Gestión ambiental, calidad del agua, muestreo. Directrices para el diseño de programas de muestreo.        
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
