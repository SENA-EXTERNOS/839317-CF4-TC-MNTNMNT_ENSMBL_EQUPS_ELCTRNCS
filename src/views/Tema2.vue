<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Equipamiento
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image':`url(${require('@/assets/curso/temas/tema2/1.jpg')})`}"
        
      )
      .bloque-texto-g__texto.p-4.w-80
        p.mb-0 A los suministros convencionales que se tenían en diversos lugares de trabajo, se han sumado medidas adicionales por COVID 19, con el fin de evitar riesgos biológicos que puedan ayudar a propagar el virus. Se requiere utilizar todos los elementos de protección necesarios que cada gobierno ponga a consideración. En este ítem, se presentan las herramientas y equipos que deben estar disponibles en un área de trabajo y la función que cumplen según las diferentes labores que se realizan.
    Separador
    #t_2_1.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 2.1 Herramientas y equipos
    .row.justify-content-center.mb-5
      .col-lg-10.position-relative
        .tarjeta.p-4.position-relative(style="background-color: #ffe6c1; width: 78%")
          .p-3.me-5
            p.mb-0 Para desempeñar un buen trabajo se debe contar con las herramientas y equipos apropiados, no se debe sustituir con elementos que se crean pueden cumplir la misma función, es necesario identificar en cuál de los dos estados lógicos de la electrónica digital se encuentra, sea por ausencia o por presencia de la tensión, diagnosticando con elementos básicos cómo puntas lógicas, obviando los equipos adecuados. (SENA, 2022)
        .imagen-absolute.d-none.d-lg-block: img(src='@/assets/curso/temas/tema2/2.svg', alt='')
    .titulo.d-flex.align-items-center.mb-4
      i.fas.fa-square.me-3(style='color: #fda929' )
      h4.mb-0 Herramientas
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5(style='border: 2px solid #20cb7d')
      .bloque-texto-g__img(
        :style="{'background-image':`url(${require('@/assets/curso/temas/tema2/3.svg')})`}"
        
      )
      .bloque-texto-g__texto.p-4.w-80
        p.mb-0 Se clasifican debido a su funcionamiento, las de uso manual, no requieren fuente de alimentación, en esta categoría están: destornilladores, alicates, pelacables, fundas termorretráctiles, bridas de plástico, guantes antiestáticos, brochas, hisopos, tercera mano con lupa. Luego están las eléctricas, que requieren de alimentación, las más conocidas: soldador o cautín, pistola de aire o de silicona, Mototool, generador de señales, fuente de alimentación, osciloscopios, sopladora o aspiradora. Y finalmente se habla de aquellas que acumulan energía para liberarla (linterna, multímetro, calibrador digital). Es de anotar, que no son las únicas herramientas y componentes que existen, se quedan muchas fuera de estas consideraciones, pero son estas las más utilizadas e importantes para las reparaciones l. (Harper, 2002)
    p.mb-5(data-aos='fade-right') En el presente capítulo, se exponen las herramientas de seguridad y de limpieza, cabe aclarar de estas son sugeridas, pero se pueden utilizar todas las necesarias para realizar las labores de cada aparato, teniendo en cuenta la gran variedad y clasificación que existen. 
    .row.justify-content-center.mb-5
      .col-lg-9(data-aos="fade-right")
        TabsA.color-secundario.mb-5
          .tarjeta.p-4(titulo="Seguridad" style='background-color: #e5e7f2').p-5
            p Básicamente se utilizan gafas de protección, guantes de nitrilo y pulsera antiestática, dependiendo de la zona de intervención también se debe usar botas de seguridad, casco y ropa adecuada. Sumando a los elementos de protección que se requieran para evitar el contagio COVID 19, según las indicaciones impartidas por los gobiernos locales.
          .tarjeta.p-4(titulo="Limpieza" style='background-color: #e5e7f2').p-5
            p Los componentes electrónicos son delicados y pueden dañarse fácilmente si no se tiene una buena manipulación e higiene, para ello se recomienda utilizar pinceles y alcohol isopropílico, además de los elementos básicos para mantener el espacio de trabajo aseado y en orden.
      .col-lg-3.col-6(data-aos="fade-left")
        .titulo-sexto.color-acento-contenido(data-aos='fade-right')
          h5 Figura 4 
          span Elementos de seguridad
        img(src='@/assets/curso/temas/tema2/4.png', alt='')
    .titulo.d-flex.align-items-center.mb-4
      i.fas.fa-square.me-3(style='color: #fda929' )
      h4.mb-0 Equipos
    .row.justify-content-center.mb-5
      .col-lg-8.position-relative
        .tarjeta.p-4.position-relative(style="background-color: #e5e7f2; width: 100%")
          .bg-card1.p-3.ms-5
            .row.justify-content-end
              .col-lg-10
                p.mb-0 En el mercado actual, existe una gran variedad de equipos electro – electrónicos, los cuales tienen un uso definido según el contexto y la tecnología con la que fueron desarrollados.
        .imagen-absolute2.d-none.d-lg-block: img(src='@/assets/curso/temas/tema2/5.svg', alt='')
    p.mb-5(data-aos='fade-right') En este apartado, se explica de manera general que son los equipos electro-electrónicos empleados para el diagnóstico, el ensamble y desmonte durante las tareas de mantenimiento y acople de dispositivos electrónicos.
    .tarjeta.bg-slyde.p-4
      SlyderA(tipo='b').p-2
        .row.justify-content-between
          .col-lg-7
            p.p-4 La valoración hace parte de las primeras acciones que se realizan al momento de efectuar la manutención de un aparato, siendo de gran importancia dar una idea inicial del estado real de los dispositivos a intervenir. Se inicia la operación con un multímetro, cables de prueba, cargador múltiple, computador y cables de comunicación. Ecosistema de Recursos Educativos Digitales (SENA, 2022)
          .col-lg-4(data-aos='fade-left')
            img(src='@/assets/curso/temas/tema2/6.png', alt='')
        .row.justify-content-between
          .col-lg-7
            p.p-4 El proceso de ensamble y desensamble es uno de los más comunes y habituales para los mantenimientos, se utilizan todo tipo de herramientas tanto manuales como especializadas, entre las más populares están los destornilladores (de distintas puntas), pinzas (de diferentes usos), alicates, llaves (de diversas formas y tamaños), así como una base articulada con lupa y luz (preferiblemente tipo LED).
              br
              br
              |Adicional, se espera contar con una zona dispuesta de manera adecuada, para realizar la intervención que brinde todas las condiciones necesarias de iluminación y ventilación.
          .col-lg-4(data-aos='fade-left')
            img(src='@/assets/curso/temas/tema2/7.png', alt='')
        .row.justify-content-between
          .col-lg-7
            .p-4
              h4 Soldado y desoldado
              p  La estación de soldadura es significativa para la reparación de dispositivos electrónicos, los componentes principales son: pistola de calor o cautín con base, soldadura de estaño plomo, líquido flux, malla de soldadura y extractor de soldadura, estos elementos son necesario tanto para el montaje de placa nuevas o como para el desarme de piezas en placas para reparar.
          .col-lg-4(data-aos='fade-left')
            img(src='@/assets/curso/temas/tema2/8.png', alt='')
    Separador
    #t_2_2.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 2.2 Procedimientos
    .row.justify-content-center.mb-5
      .col-lg-7(data-aos="fade-right")
        .cajonb-editado-azul
          .cajon-b.color-acento-contenido.abajo-derecha.p-3.mb-5
            p.mb-0 Para realizar la inspección inicial de un equipo eléctrico o electrónico, se debe de llevar a cabo una serie de pasos ordenados. Cabe aclarar que los procedimientos varían dependiendo de los dispositivos a intervenir. Al detectar algún tipo de falla es necesario determinar la posible causa que la origina, dado que por lo general hay un comportamiento inusual en el aparato, como ruidos, expulsión de humo, olores, goteo de fluidos, etc. Siempre es recomendado consultar los manuales para revisar los métodos de funcionamiento y de uso del artefacto, para descartar la posibilidad de fallas humanas, en caso de no detectarse algo así, se debe Investigar el origen del problema, chequear factores externos que afectan el dispositivo para su posterior daño, verificar si existen daños físicos externos, revisión de los controles, operar el equipo con sus funciones básicas para examinar el desperfecto, si no enciende se debe detectar el o los componentes que fallen para su reemplazo, durante todo el trámite se recomienda estar atento a la presencia de ruidos, chispas, olores, emisiones de humo o cualquier anomalía inusual que afecte el aparato. (SENA, 2022)
      .col-lg-5.col-8(data-aos="fade-left")
        .titulo-sexto.color-acento-contenido(data-aos='fade-right')
          h5 Figura 8.
          span Mantenimiento de equipos electrónicos 
        img(src='@/assets/curso/temas/tema2/9.png', alt='')
    p.mb-5(data-aos='fade-right') En la siguiente sección se presentan los pasos a seguir durante los diferentes procedimientos con equipos electrónicos, es importante seguirlos para realizar las actividades de una forma técnica y coherente, reconociendo la importancia de estos. Los procedimientos son recomendaciones que dan personas u organizaciones que han tenido mayor experiencia en la planeación o ejecución de cierta actividad, por este motivo se hacen para los mantenimientos. 
    .tarjeta.bg-pasos.p-4.mb-5
      PasosB.color-acento-botones.p-4
        .row(titulo="")
          .col-lg-7.mb-4.mb-md-0
            h4 Verificar las conexiones

            p Sin importar cual sea el equipo a intervenir, se debe de constatar que no esté conectado a una fuente de energía. Es uno de los errores más comunes y pueden generar daños más grandes en los aparatos; esta es una recomendación general que debe ser tenida en cuenta para la manipulación de cualquier dispositivo sin importar el tamaño o la ubicación dentro del hogar o en la industria.
              br
              br
              |El tipo de terminal de la conexión que tiene el equipo y las condiciones técnicas que tiene cada aparato se deben verificar desde el inicio; aunque la mayoría vienen homologados para el continente americano, no todos tienen las mismas especificaciones de conexión, en Colombia la frecuencia es 60 Hz, el voltaje común es 110 V para artefactos utilizados en el hogar. Las clavijas y enchufes son del tipo A / B. En caso de requerir tomacorrientes, se debe de evitar la conexión de aquellas situadas en las instalaciones, dado que puede ocasionar un corto circuito 
              span(@click="modal1= true" ).vermas (Ver +).
          .col-lg-5.col-8
            img(src='@/assets/curso/temas/tema2/19.png', alt='')
        .row(titulo="")
          .col-lg-7.mb-4.mb-md-0
            h4 Consultar el manual
            p Seguir las instrucciones dadas por el fabricante es fundamental para evitar daños o posibles pérdidas de garantía. Se aconseja tener el manual a la mano, realizar consultas rápidas con respecto a acciones sencillas, inspecciones simples o intervenciones rápidas. Este proceso lo puede hacer una persona con o sin conocimientos técnicos, proporcionando respuestas a supuestas fallas sólo con cambiar el modo de operación del aparato. (Harper, 2002)
          .col-lg-5.col-8
            img(src='@/assets/curso/temas/tema2/10.png', alt='')
        .row(titulo="")
          .col-lg-7.mb-4.mb-md-0
            h4 Alistamiento de herramientas
            p Disponer de las herramientas necesarias, con una disposición adecuada y ordenada, evita reprocesos y accidentes. Lo anterior se considera dentro de las buenas prácticas de taller y permite optimizar los tiempos, los materiales y la disminución de posibles errores.
          .col-lg-5.col-8
            img(src='@/assets/curso/temas/tema2/11.png', alt='')
        .row(titulo="")
          .col-lg-7.mb-4.mb-md-0
            h4 Desarmado exterior
            p Para retirar las partes, es clave ubicar los elementos móviles de la parte exterior, tales como tornillos, pernos, pasadores, en un lugar determinado y apartado, para sortear la pérdida de los componentes. Es importante prevenir reprocesos, por ello se sugiere no realizar varias intervenciones de aparatos al tiempo y en un mismo lugar, así se disminuyen las confusiones en los componentes, los cuales por sus características visuales son muy similares entre sí, especialmente los tornillos de sujeción exterior. 
          .col-lg-5.col-8
            img(src='@/assets/curso/temas/tema2/12.png', alt='')
        .row(titulo="")
          .col-lg-7.mb-4.mb-md-0
            h4 Desarme de partes móviles
            p Para el desarme de las partes móviles internas de los aparatos, es necesario quitar las carcasas y tapas que cubren el aparato, moviéndolo de forma segura y adecuada. Siempre se deben almacenar las partes de forma ordenada, para evitar daños de los componentes mecánicos o electrónicos. Los elementos móviles de tipo mecánico, tipo tornillos, arandelas, pasadores, etc., al igual que los componentes encapsulados, como condensadores, resistencias, diodos, entre muchos más, suelen ser diminutos y tienden a perderse o confundirse con facilidad, es recomendable destinar un recipiente en el cual se puedan ubicar para evitar inconvenientes o pérdidas. 
          .col-lg-5.col-8
            img(src='@/assets/curso/temas/tema2/13.png', alt='')
        .row(titulo="")
          .col-lg-7.mb-4.mb-md-0
            h4 Inspección inicial
            p Se comienza con un ejercicio de inspección visual, detectando rápidamente las posibles fallas, como desconexiones, cortocircuitos, entre otros. 
          .col-lg-5.col-8
            img(src='@/assets/curso/temas/tema2/14.png', alt='')
        .row(titulo="")
          .col-lg-7.mb-4.mb-md-0
            h4 Identifique las referencias de los componentes
            p Ubicado en la hoja de datos los terminales de cada uno de ellos y la forma correcta de trabajo, se efectúa la revisión de los componentes, es necesario tener en cuenta las marcas, dado que puede tener variaciones.
          .col-lg-5.col-8
            img(src='@/assets/curso/temas/tema2/15.png', alt='')
        .row(titulo="")
          .col-lg-7.mb-4.mb-md-0
            h4 Inventario
            p En esta fase, es importante para las organizaciones, contar con un stock de repuestos, el cual debe ser dinámico y tener gran variedad que ayude a reducir los tiempos de consecución de las partes. Si bien, es difícil tener a la mano todos los componentes que se necesitan para una reparación, si existen algunos que son muy comunes y empleados en diferentes circuitos. Es recomendado sistematizar este proceso para que se puedan adquirir los utensilios de una forma eficiente y ordenada  (Mora, L. 2016).
          .col-lg-5.col-8
            img(src='@/assets/curso/temas/tema2/16.png', alt='')
        .row(titulo="")
          .col-lg-7.mb-4.mb-md-0
            h4 Proveedores
            p Es importante contar con un proveedor local, que responda rápidamente a las necesidades del mercado y suministre con prontitud los insumos requeridos. El tener proveedores facilita la competitividad en el mercado, es relevante contar con distribuidores locales y externos, para facilitar y garantizar los insumos solicitados en las  reparaciones o creaciones de nuevos circuitos, se aclara este punto teniendo en cuenta la globalización de los mercados y la constante variación de los componentes, dado que la mayoría de los insumos utilizados en la electrónica, son producidos en el extranjero y deben ser importados, lo cual influye en los tiempos de intervención de los dispositivos y en los costos, (Arrow Electronics, (2022) y Mora, L. (2016)).
          .col-lg-5.col-8
            img(src='@/assets/curso/temas/tema2/20.png', alt='')
        .row(titulo="")
          .col-lg-7.mb-4.mb-md-0
            h4 Pruebas
            p Después de realizar el reemplazo o reparación, se procede a hacer ensayos de funcionamiento, es importante seguir las normas de seguridad y las instrucciones de manipulación proporcionadas por el fabricante. Se recomienda hacer una verificación de cada sistema por separado para ir garantizando el óptimo funcionamiento.
          .col-lg-5.col-8
            img(src='@/assets/curso/temas/tema2/17.png', alt='')
        .row(titulo="")
          .col-lg-7.mb-4.mb-md-0
            h4 Armado
            p Este procedimiento es el último para ensamblar el equipo, para ello se hace una inspección final de funcionamiento y una limpieza profunda, dado que se pueden dejar marcas en su estructura.
          .col-lg-5.col-8
            img(src='@/assets/curso/temas/tema2/18.png', alt='')
    .modal-azul
      ModalA(:abrir-modal.sync="modal1" )
        p  El enchufe tipo A es el estandarizado para Norte América y América Central, son muy similares a los tomacorriente y enchufes japoneses. Este enchufe no tiene conexión a tierra, se utilizaba antes en Colombia, tiene dos clavijas planas paralelas entre sí y no tiene conexión a línea tierra. En caso de no contar con los tomacorrientes tipo B (clavijas planas paralelas y una redonda) No se debe retirar la clavija redonda para que se pueda utilizar. Se recomienda utilizar un convertidor de clavijas de Tipo B a tipo A.
          br
          br
          |El enchufe tipo B es el implementado en Colombia. Este enchufe tiene conexión a tierra en una tercera clavija de forma redonda, que es la diferencia más grande con el enchufe tipo A, además tiene dos clavijas planas paralelas entre sí. Es el tipo de conexión más común en todos los aparatos eléctricos y electrónicos que se encuentran en Colombia, son usuales en los televisores, videobeam, neveras, hornos microondas, ollas y sartenes eléctricos, planchas, computadores, estabilizadores, extensiones, celulares entre muchos otros. (UPB, 2021). Cabe anotar que este tipo de conector puede utilizar en un enchufe tipo A utilizando un convertidor de dos clavijas planas paralelas y una redonda (tipo B) a uno de dos clavijas planas paralelas (tipo A).
    Separador
    #t_2_3.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 2.3 Fichas y manuales
    .row.justify-content-center.mb-5
      .col-lg-8.position-relative
        .tarjeta.p-4.position-relative(style="background-color: #b1edd1; width: 100%")
          .bg-card.p-3.ms-5
            .row.justify-content-end
              .col-lg-10
                p.mb-0 Hace referencia a los documentos que pueden ser entregados por los proveedores o creados por la empresa para dar indicaciones propias. Contienen información valiosa y especifica de cada aparato. 
        .imagen-absolute2.d-none.d-lg-block: img(src='@/assets/curso/temas/tema2/21.svg', alt='')
    .bg-form.p-5.mb-5
      .titulo.d-flex.align-items-center.mb-4
        i.fas.fa-square.me-3(style='color: #fda929' )
        h4.mb-0 Fichas
      .row.justify-content-center.mb-5
        .col-lg-5(data-aos="fade-right")
          p Es el reporte que brinda el fabricante o proveedores a los usuarios; se conoce como ficha técnica o de características, hoja de datos, hoja técnica, allí se consigna información especializada del aparato eléctrico o electrónico, haciendo referencia a todos los componentes o subsistemas electrónicos, que puedan ser empleados por personal técnico. Estos manuales varían dependiendo del equipo, las regulaciones de las industrias a la que pertenece el dispositivo y del fabricante, (Altium Limited, 2020)
        .col-lg-5(data-aos="fade-left")
          .titulo-sexto.color-acento-contenido(data-aos='fade-right')
            h5 Figura 9.
            span Ejemplo de hojas de datos de componentes 
          img(src='@/assets/curso/temas/tema2/22.png', alt='').mb-3
          figcaption(style='background-color: #f6f1ff') Nota: Adaptada de Hoja de datos LED-530LB5C (PDF) (2022). Componentes electrónicos HB. Alldatasheet.
    p.mb-5(data-aos='fade-right') A continuación, se resaltan algunos aspectos principales, es importante aclarar que este documento contiene información técnica, muy específica que debe ser interpretada por personal capacitado, referente al tipo de conexión, instalación, montaje, etc.
    TabsC.color-secundario.mb-5
      .bg-form.p-5.py-md-5(titulo="Descripción general")
        .row
          .col-md-3: img(src='@/assets/curso/temas/tema2/23.svg', alt='')
          .col-md-9.mb-4.mb-md-0
            p Hace referencia a los detalles externos y a las características más relevantes de los componentes, cabe anotar que se especifican datos sobresalientes de la apariencia externa y de la parte estética del equipo, (Alldatasheet, 2022).
      .bg-form.p-5.py-md-5(titulo="Valores")
        .row
          .col-md-3: img(src='@/assets/curso/temas/tema2/24.svg', alt='')
          .col-md-9.mb-4.mb-md-0
            p Corresponde a los valores máximos y mínimos que determinan a cada elemento. Son los rangos de operación que requiere el dispositivo para el funcionamiento correcto. 
      .bg-form.p-5.py-md-5(titulo="Circuito electrónico")
        .row
          .col-md-3: img(src='@/assets/curso/temas/tema2/25.svg', alt='')
          .col-md-9.mb-4.mb-md-0
            p Son generalmente las placas PCB (Printed Circuit Board - Placas de Circuito Impreso), las cuales contienen diferentes tipos de componentes, traen información técnica necesaria para ser manipulada e intervenida en mediciones y pruebas.
      .bg-form.p-5.py-md-5(titulo="Características de los elementos")
        .row
          .col-md-3: img(src='@/assets/curso/temas/tema2/26.svg', alt='')
          .col-md-9.mb-4.mb-md-0
            p #[b Mecánicas]
              br
              |Los elementos mecánicos contienen las características básicas de los elementos de este tipo, entre los más comunes se pueden ver tornillos, pasadores, piñones, ejes, etc., entre las más importantes se encuentran las dimensiones y el material. Hace referencia al montaje y procesos que realiza el aparato. Son elementos que requieren de un accionamiento o fuerza para su funcionamiento, forman parte de los mecanismos móviles o de la estructura del aparato.
              br
              br
              |#[b Electrónicas]
              br
              |Presentan las características de los componentes electrónicos, con sus respectivos gráficos básicos de las funciones de electrónica, tales como su modo correcto de ubicación, ensamble y conexión. Requiere de diferentes conocimientos e  interpretaciones técnicas, haciéndolo de forma ordenada y lógica. Contiene especificaciones tales como planos, esquemas, diagramas de flujo interpretados por personal capacitado y con algún nivel de formación técnica. No resulta ser tan comprensible para la mayoría de las personas del común. 
    .titulo.d-flex.align-items-center.mb-4
      i.fas.fa-square.me-3(style='color: #fda929' )
      h4.mb-0 Manuales de servicio
    .row.justify-content-center.mb-5
      .col-lg-8.position-relative
        .tarjeta.p-4.position-relative(style="background-color: #e5e7f2; width: 100%")
          .bg-card1.p-3.ms-5
            .row.justify-content-end
              .col-lg-10
                p.mb-0 Son instructivos, donde los fabricantes o proveedores explican las pautas del mantenimiento, los repuestos que se deben de tener a la mano y las fallas más comunes, así como todos los protocolos de seguridad necesarios, este documento es de carácter más general para el público y los usuarios, no requiere de un alto grado de capacitación para su entendimiento, diferente a las fichas que contienen información más técnica,  (Harper, 2002). 
        .imagen-absolute3.d-none.d-lg-block: img(src='@/assets/curso/temas/tema2/27.svg', alt='')
    .bg-linea-tiempo.p-5 
      p.mb-5(data-aos='fade-right') A continuación, se explican las principales partes de los manuales de servicio, entendiendo que es un documento que ayuda a la resolver problemas simples, que pueden ser solucionados por el usuario o personal con poca capacitación, teniendo en cuenta que puede o no ser solucionado el error común presentado que se encuentre en la lista de problemas frecuentes para ese equipo.
      .row.justify-content-center.mb-5
        .col-lg-10.text-start
          PasosA.color-secundario.mb-5(tipo="n")
            .row(titulo="").justify-content-between
              .col-md-6.mb-4.mb-md-0
                h4 Portada
                p Se hace referencia al nombre, modelo y una imagen, lo más ilustrativo del aparato electrónico, cada manual puede tener información diferente dependiendo del fabricante y de los lugares del mundo donde se realice.
              .col-md-2.col-6: img(src='@/assets/curso/temas/tema2/28.svg', alt='')
            .row(titulo="").justify-content-between
              .col-md-2.col-6: img(src='@/assets/curso/temas/tema2/29.svg', alt='')
              .col-md-6.mb-4.mb-md-0
                h4 Operación básica
                p Se presenta una vista general del equipo, funcionamiento básico, botones de acceso principales, así como las tablas y diagramas principales. Es una guía sencilla y rápida donde el usuario puede guiarse para realizar las tareas más sencillas del equipo.
            .row(titulo="").justify-content-between
              .col-md-6.mb-4.mb-md-0
                h4 Información del hardware
                p Se enseñan los diagramas electrónicos principales, piezas mecánicas y componentes necesarios, utilizados en el aparato. Se representan los esquemas más importantes, pueden ser una o varias, teniendo en cuenta la cantidad de sistemas principales que tenga el equipo.
              .col-md-2.col-6: img(src='@/assets/curso/temas/tema2/30.svg', alt='')
            .row(titulo="").justify-content-between
              .col-md-2.col-6: img(src='@/assets/curso/temas/tema2/31.svg', alt='')
              .col-md-6.mb-4.mb-md-0
                h4 Información del software
                p Si son aparatos con pantallas de visualización, se debe revisar el sistema operativo, para la actualización y compatibilidad con los otros dispositivos.
            .row(titulo="").justify-content-between
              .col-md-6.mb-4.mb-md-0
                h4 Solución de problemas
                p Se hace una lista, que contenga problemas frecuentes o los menos habituales, cada uno con una solución sencilla interviniendo el componente que se requiere.
                  br
                  br
                  |Una buena opción para el arreglo de las fallas que se presentan de manera constante, es el reemplazo o iniciación de proyectos electrónicos, es la implementación de Impresoras 3D, para el diseño de partes externas y cambio de piezas averiadas, etc.
              .col-md-2.col-6: img(src='@/assets/curso/temas/tema2/32.svg', alt='')
              

</template>

<script>
import Separador from 'ecored-base-pkg/src/components/Separador.vue'
export default {
  name: 'Tema2',
  components: { Separador },
  data: () => ({
    modal1: false,
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

<style lang="sass">
.imagen-absolute
  position: absolute
  bottom: 0
  right: 0
  transform: translate(10%, 20%)
.imagen-absolute2
  position: absolute
  bottom: 0
  left: 0
  transform: translate(-40%, 20%)
.imagen-absolute3
  position: absolute
  bottom: 0
  left: 0
  transform: translate(-40%, 5%)
.tabs-a.color-secundario .tabs-a__tab__selected .tabs-a.color-secundario .tabs-a__tab__selected:before
  background-color: #33438f !important
.bg-slyde
  background-image: url('../assets/curso/temas/tema2/bg-slyde.svg')
  background-size: cover
  background-position: center
  background-repeat: no-repeat
  .slyder-a__btn--sigt, .slyder-a__btn--atrs
    background-color: #ffca79
    border: none
  .slyder-a__bullets__item
    background-color: #fee1b4
    border: none
  .slyder-a__bullets__item--active
    background-color: #ffca79 !important
      border: none
.cajonb-editado-azul
  .cajon-b::before
    background-color: #def7ec !important
    opacity: 1 !important
.bg-pasos
  background-image: url('../assets/curso/temas/tema2/bg-pasos.svg')
  background-size: cover
  background-position: center
  background-repeat: no-repeat
.bg-form
  background-image: url('../assets/curso/temas/tema2/bg-form.svg')
  background-size: cover
  background-position: end
  background-repeat: no-repeat

.modal-azul
  .modal-a__content
    background-color: #29398a
    p
      color: #fff
  .modal-a__close-btn i
    color: #fff
.pasos-b__header__item--before .pasos-b__header__item__dot
  background-color: #7453d8
  border: none
.pasos-b__header__item--before .pasos-b__header__item__line-container:after
  background-color: #7453d8 !important
.pasos-b__header__item--active .pasos-b__header__item__line-container:before
  background-color: #7453d8 !important
.pasos-b__header__item--before .pasos-b__header__item__line-container:before
  background-color: #7453d8 !important
.pasos-b__header__btn--left, .pasos-b__header__btn--right
  background-color: #ffca79
  border: none
.bg-linea-tiempo
  background-image: url('../assets/curso/temas/tema2/bg-linea-tiempo.svg')
  background-size: cover
  background-position: start
  background-repeat: no-repeat
  margin: 0 -3rem
</style>
