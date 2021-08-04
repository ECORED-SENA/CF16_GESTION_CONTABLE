<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 2
      h1 Nómina de producción
    p Es momento de abordar las generalidades de la nómina de producción, teniendo en cuenta que esta aplica para empresas que fabrican bienes. De acuerdo con la naturaleza de la actividad desempeñada por el colaborador, la nómina se divide en los siguientes:   
    .row
      .col-lg-8.justify-content-start
        figure.mb-5
          img.mb-2(src="@/assets/tema2/img-1.svg")
    separador
    
    #t_2_1.titulo-segundo
      h2 2.1 Concepto
    p La nómina es un documento en el cual se refleja el pago a los empleados a cambio de realizar un trabajo determinado. Es el resumen de todos los registros contables para realizar el pago a los colaboradores, donde se encuentra el registro del salario, días laborados, devengos, deducciones y apropiaciones para finalmente saber cuál es el neto para pagar a cada empleado.
    p Según la Norma Internacional de Contabilidad (NIC 19), se definen los beneficios a los empleados, así:
    .row.justify-content-around.align-items-center.p-3
      .col-lg.justify-content-md-center.align-self-center.px-5
        .ul.lista-ul--color
          li 
            i.fas.fa-check
            p Beneficios a los empleados son todas las formas de contraprestación concedidas por una entidad a cambio de los servicios prestados por los empleados o por indemnizaciones por cese.
          li 
            i.fas.fa-check
            p Beneficios a los empleados a corto plazo, son beneficios a los empleados (diferentes de las indemnizaciones por cese) que se espera liquidar totalmente antes de los doce meses siguientes al final del periodo anual sobre el que se informa, en el que los empleados hayan prestado los servicios relacionados.
          li 
            i.fas.fa-check
            p Beneficios post-empleo son beneficios a los empleados (diferentes de las indemnizaciones por cese y beneficios a los empleados a corto plazo) que se pagan después de completar su periodo de empleo.
          li 
            i.fas.fa-check
            p Otros beneficios a los empleados a largo plazo son todos los beneficios a los empleados diferentes de los beneficios a los empleados a corto plazo, beneficios posteriores al periodo de empleo e indemnizaciones por cese.

      .col-12.col-lg-auto.justify-content-md-center.mb-4  
        figure.mb-5
          img.img-450.mb-2(src="@/assets/tema2/img-2.svg")

    p Los beneficios a los empleados comprenden: 

    AcordionA.mb-5(tipo="b" clase-tarjeta="tarjeta tarjeta--azul fondo4")
      .row.t-l.px-2(titulo="Beneficios a corto plazo")
        p Si se esperan liquidar totalmente antes de los doce meses posteriores al final del periodo anual sobre el que se informa, en el que los empleados presten los servicios relacionados: 
        .ul.lista-ul--color.px-5
          li 
            i.fas.fa-check
            p Sueldos, salarios y aportaciones a la seguridad social.
          li 
            i.fas.fa-check
            p Derechos por permisos y ausencia retribuidos por enfermedad.
          li 
            i.fas.fa-check
            p Participación en ganancias e incentivos.
          li 
            i.fas.fa-check
            p Beneficios no monetarios a los empleados actuales (tales como atenciones médicas, alojamiento, automóviles y entrega de bienes y servicios gratuitos o parcialmente subvencionados).


      div(titulo="Beneficios post-empleo")
     
        p Tales como los siguientes: 
        .ul.lista-ul--color.px-5
          li 
            i.fas.fa-check
            p Beneficios por retiro (por ejemplo, pensiones y pagos únicos por retiro); y
          li 
            i.fas.fa-check
            p Otros beneficios post-empleo, tales como los seguros de vida y los beneficios de atención médica posteriores al empleo.           

      div(titulo="Otros beneficios a los empleados a largo plazo")
     
        p Tales como los siguientes: 
        .ul.lista-ul--color.px-5
          li 
            i.fas.fa-check
            p Las ausencias retribuidas a largo plazo, tales como vacaciones tras largos periodos de servicio o años sabáticos;
          li 
            i.fas.fa-check
            p Los premios de antigüedad u otros beneficios por largo tiempo de servicio; 
          li 
            i.fas.fa-check
            p Los beneficios por invalidez permanente; 
          li 
            i.fas.fa-check
            p Beneficios por terminación. Norma Internacional de Contabilidad (NIC 19, s.f., p.1-46).
    
    .row.justify-content-around.align-items-center
      .col-lg-10.justify-content-md-center.align-self-center
        .tarjeta.color-primario.mb-5.fond3.px-4.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/tema1/img-10.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.mb-1.texto-blanco.text-bold Con el fin de profundizar sobre la Norma Internacional (NIC) 19, se sugiere explorar los siguientes enlaces: 
                  
                .col-sm-auto
                  a.mb-2.boton.color-acento-botones(:href="obtenerLink('/downloads/19_NIC.pdf')" target="_blank")
                    span.px-4 Descargar  
                    i.fas.fa-download 
                  br    
                  a.mb-3.boton.color-acento-botones(:href="obtenerLink('/downloads/nic-19.pdf')" target="_blank")
                    span.px-4 Descargar  
                    i.fas.fa-download                                 

    separador
    #t_2_2.titulo-segundo
      h2 2.2 Elementos de la nómina de producción
      
    .row  
      .col-lg.justify-content-start
        p La nómina está compuesta por:    
        ol.lista-ol--cuadro
            li 
              .lista-ol--cuadro__vineta
                span 1
              | Datos de la empresa y dirección del centro de trabajo.
            li 
              .lista-ol--cuadro__vineta
                span 2
              | Fecha del periodo de cotización de la nómina.
            li 
              .lista-ol--cuadro__vineta
                span 3
              | Debe decir explícitamente a qué área o departamento pertenece la nómina. 
            li 
              .lista-ol--cuadro__vineta
                span 4
              | Datos básicos del trabajador, tipo de contrato, número de días laborados.
            li 
              .lista-ol--cuadro__vineta
                span 5
              | Salario y prestaciones extrasalariales.
            li 
              .lista-ol--cuadro__vineta
                span 6
              | Detalle de todas las deducciones que se practican en el periodo y que estén constituidas legalmente.
            li 
              .lista-ol--cuadro__vineta
                span 7
              | Apropiaciones que tengan lugar en el periodo de tiempo.
            li 
              .lista-ol--cuadro__vineta
                span 8
              | Líquido para percibir.
            li 
              .lista-ol--cuadro__vineta
                span 9
              | Detalle de las bases de cotización.
            li 
              .lista-ol--cuadro__vineta
                span 10
              | Lugar de emisión y firma del empleador si hay lugar a esta.

      .col-12.col-lg-auto.justify-content-md-center.mb-4  
        figure.mb-5
          img.img-450.mb-2(src="@/assets/tema2/img-3.svg")


    h3 Devengado
    p El devengado es el valor total de ingresos que obtiene un empleado en un periodo de tiempo determinado. El devengo está compuesto por el salario básico, horas extras, recargos diurnos y nocturnos, dominicales, festivos, comisiones, auxilio de transporte, entre otras (Gerencie, 2017).
    .row 
      .col-lg.justify-content-start
        p El artículo 127 del Código Sustantivo del Trabajo expresa: 
        .cajon.color-primario.p-4.mb-4.fond2
            p Constituye salario no sólo la remuneración ordinaria, fija o variable, sino todo lo que recibe el trabajador en dinero o en especie como contraprestación directa del servicio, sea cualquiera la forma o denominación que se adopte, como primas, sobresueldos, bonificaciones habituales, valor del trabajo suplementario o de las horas extras, valor del trabajo en días de descanso obligatorio, porcentajes sobre ventas y comisiones (Gerencie, 2020).

      .col-12.col-lg-auto.justify-content-md-center.mb-4.mx-5 
        figure
          img.img-250.mb-2(src="@/assets/tema2/img-4.svg")
    h3 Salario
    
    p De acuerdo con lo anterior, el salario es la cantidad de dinero que recibe un trabajador por desarrollar su función sin que se le realice ningún descuento.

    h3 Salario básico

    p Es el valor acordado en el contrato laboral y la base para determinar las horas extras y recargos.

    h3 Salario integral

    p Se encuentra conformado por 13 salarios mínimos mensuales legales vigentes (SMMLV). El salario compensa prestaciones sociales, recargos y beneficios que correspondan al colaborador de acuerdo con la normativa legal o convencional.

    h3 Mano de obra directa

    p Son los salarios que se les pagan a las personas que participan directamente en la transformación de la materia prima en producto terminado y se puede identificar o cuantificar plenamente en el producto terminado.

    h3 Mano de obra indirecta

    p Son los salarios y sueldos que se pagan al personal de apoyo a la producción, y que no se pueden identificar o cuantificar plenamente con la elaboración de productos.

    h3 Hora-hombre

    p Es la manera para cuantificar las horas de intervención de personas en un proceso y permite establecer el costo de mano de obra directa de un proceso; también es útil para determinar la eficiencia.

    h3 Remuneración trabajo ordinario y suplementario

    p Según la jornada laboral acordada entre las partes y la efectivamente desarrollada, se puede presentar trabajo suplementario relacionado a continuación: 
 
    .row.mx-4.fond6.mb-5
      LineaTiempoB.color-secundario.mb-5(:datos="datosLineaTiempoB")
    
    .row.justify-content-around.align-items-center.mb-5.mx-4
      .col-lg-10.justify-content-md-center.align-self-center    
        .tabla-b.color-acento-contenido.mb-5
    
            
          table
            caption Fuente: Arts. 168 y 179 CST
            thead
              tr.tb-h
                th.r-r  CLASE DE TRABAJO 
                th.r-r  RECARGO % 
                th.r-r  FACTOR 
            tbody
              tr
                td  Extra diurno ordinario 
                td.b-c.text-center 25 
                td.text-center 1.25 
              tr
                td  Extra nocturno ordinario 
                td.b-c.text-center  75 
                td.text-center 1.75 
              tr
                td  Dominical y festivo 
                td.b-c.text-center   75 
                td.text-center 1.75 
              tr
                td  Dominical y festivo nocturno 
                td.b-c.text-center   110 
                td.text-center 2.10 
              tr
                td  Extra diurno festivo 
                td.b-c.text-center   100 
                td.text-center 2.00 
              tr
                td  Extra nocturno festivo 
                td.b-c.text-center   150 
                td.text-center 2.50 
              tr
                td  Recargo nocturno 
                td.b-c.text-center   35 
                td.text-center 0.35 

    p.r-n.text-bold Flujo de la distribución de la nómina de fábrica

    .row.justify-content-around.align-items-center.mb-5
      .col-lg-8.justify-content-around.align-items-center
        figure.mb-5
          img.mb-2.img-450(src="@/assets/tema2/img-12.svg")
          figcaption Tomada de Sinisterra (2017).

    h3 Deducciones
    p Son el valor que se le descuenta a cada trabajador. Entre estos están los aportes a salud y pensión que le corresponden al empleado, las libranzas, los embargos judiciales, la retención en la fuente si hubiere, y cualquier otro descuento autorizado por el empleado (Gerencie, 2017).
    p Conceptos principales para descontar al trabajador:
    .row.justify-content-around.align-items-center.p-3
      .col-lg.justify-content-md-center.align-self-center.px-5
        .ul.lista-ul--color
          li 
            i.fas.fa-check
            p Aportes a salud 4%.
          li 
            i.fas.fa-check
            p Aportes a pensión 4%.
          li 
            i.fas.fa-check
            p Aportes a fondo de solidaridad pensional, el porcentaje depende del valor devengado y comienza desde 1% para los trabajadores que devenguen en el periodo cuatro o más salarios mínimos legales vigentes. 
          li 
            i.fas.fa-check
            p Cuotas sindicales.
          li 
            i.fas.fa-check
            p Aportes a cooperativas.
          li 
            i.fas.fa-check
            p Embargos judiciales.
          li 
            i.fas.fa-check
            p Cuotas o créditos a entidades financieras “libranza”.
          li 
            i.fas.fa-check
            p Deudas del trabajador con la entidad o empresa.
          li 
            i.fas.fa-check
            p Retención en la fuente.


      .col-12.col-lg-auto.justify-content-md-center.mb-4  
        figure.mb-5
          img.img-450.mb-2(src="@/assets/tema2/img-13.svg")

    h3 Seguridad social y parafiscales
    p.mb-5 A continuación, se relacionan las siguientes definiciones: 
    .row.justify-content-around.align-items-center.mb-5
      .col-11.justify-content-around.align-items-center
        .crd_01.mb-3
          .crd_01__icon
            img(src="@/assets/tema2/img-14.svg", alt="alt").class          
          .crd_01__txt
            p.text-bold Seguridad Social. 
            p Es el derecho que tiene toda persona natural, y en especial todo trabajador, a que se le garantice la seguridad social integral, entendida ésta como la cobertura en salud, riesgos de invalidez, vejez y muerte, igualmente cobertura en accidentes de trabajo (Gerencie, 2018).
        .crd_01.mb-5
          .crd_01__icon
            img(src="@/assets/tema2/img-15.svg", alt="alt").class          
          .crd_01__txt
            p.text-bold Parafiscales. 
            p Son los pagos que las entidades o empresas y personas naturales realizan a: Servicio Nacional de Aprendizaje SENA, Instituto Colombiano de Bienestar Familiar ICBF y Caja de Compensación Familiar CCF con el propósito de financiar actividades sociales que presta el estado por intermedio de estas entidades.
        .bloque-texto-d.color-secundario.p-4.mb-5.aaa 
            .bloque-texto-d__texto.mb-2
              i.fas.fa-quote-left
              h3.text-regular Estarán exoneradas del pago de los aportes parafiscales a favor del Servicio Nacional de Aprendizaje (SENA), del Instituto Colombiano de Bienestar Familiar (ICBF) y las cotizaciones al Régimen Contributivo de Salud, las sociedades y personas jurídicas y asimiladas contribuyentes declarantes del impuesto sobre la renta y complementarios, correspondientes a los trabajadores que devenguen, individualmente considerados, menos de diez (10) salarios mínimos mensuales legales vigentes.

            .bloque-texto-d__autor 
              .h5.mb-0 Art.114-1 del Estatuto Tributario. Exoneración de aportes - 
                i.fas.fa-quote-right

    p.mb-5 Así mismo, las personas naturales empleadoras estarán exoneradas de la obligación de pago de los aportes parafiscales al SENA, al ICBF y al Sistema de Seguridad Social en Salud por los empleados que devenguen menos de diez (10) salarios mínimos legales mensuales vigentes. Lo anterior no aplicará para personas naturales que empleen menos de dos trabajadores, los cuales seguirán obligados a efectuar los aportes de que trata este inciso (Accounter, 2017).
    
    h3 Las apropiaciones
    p Son los pagos que la empresa debe hacer sobre la nómina, que son adicionales a los pagos que hace al trabajador, y que están a cargo en su totalidad.
    p Aportes a la seguridad social y parafiscales:

    .tabla-b.color-acento-contenido.mb-5.px-5
         
      table
        thead
          tr.tb-h
            th.r-r  TIPO DE ENTIDAD 
            th.r-r  % APORTE EMPLEADOR 
            th.r-r  % APORTE EMPLEADO 
            th.r-r  % TOTAL APORTE 
        tbody
          tr
            td.text-bold  Salud 
            td.b-c.text-center  8.5% 
            td.b-c.text-center  4% 
            td.text-center  12.5% 
          tr
            td.text-bold   Pensi&oacute;n 
            td.b-c.text-center  12% 
            td.b-c.text-center  4% 
            td.text-center  16% 
          tr
            td.text-bold   *ARL 
            td.b-c.text-center  0.522% 
            td.b-c.text-center  0% 
            td.text-center  0.522% 
          tr
            td.text-bold   **Fondo de solidaridad 
            td.b-c.text-center  0% 
            td.b-c.text-center  1% 
            td.text-center  1% 
          tr
            td.text-bold   Caja de compensaci&oacute;n 
            td.b-c.text-center  4% 
            td.b-c.text-center  0% 
            td.text-center  4% 
          tr
            td.text-bold  ICBF 
            td.b-c.text-center  3% 
            td.b-c.text-center  0% 
            td.text-center  3% 
          tr
            td.text-bold  SENA 
            td.b-c.text-center  2% 
            td.b-c.text-center  0% 
            td.text-center  2% 
    
    h3 ARL
    p.mb-5 La cotización de ARL varía según el riesgo a que se exponga cada trabajador y es pagada en su totalidad por el empleador. Los aportes varían entre un 0,348% para el nivel I y 8,7% para el nivel V de riesgo. La tarifa más común es del 0,522%.

    h3 Fondo de solidaridad
    p Los trabajadores con sueldos entre 4 y 16 salarios mínimos deben realizar un aporte adicional del 1%. 
 
    p.mb-5 Los trabajadores que devenguen mensualmente 16 salarios mínimos o más, adicional al 1%, deben hacer un aporte adicional del 0,2% por cada sueldo mínimo adicional que devenguen hasta los 20 salarios mínimos.

    h3 Prestaciones sociales
    p.mb-5 Es el conjunto de beneficios adicionales al salario que la ley ha otorgado a los trabajadores con el fin de contribuir a su bienestar; constituyen un gasto de los empleadores, quienes deben causarse o reconocerlos con cargo a los gastos por prestaciones sociales que adeudan a los trabajadores y constituir las provisiones sobre su nómina mensual.

    h3 Cesantías
    p.mb-5 Corresponden a 30 días por año trabajado; se deben liquidar al final de cada año o al finalizar el contrato de trabajo. El valor liquidado se debe consignar en el fondo de cesantías que el empleado haya elegido, y en el caso de terminación del contrato de trabajo, el valor liquidado se paga directamente al trabajador.

    h3 Intereses sobre cesantías
    p.mb-5 El empleador debe pagar a sus empleados intereses sobre las cesantías que tenga acumuladas a 31 de diciembre, a una tasa del 12% anual.

    h3 Prima de servicios
    p.mb-5 Corresponde a 30 días por año trabajado; se debe pagar en dos cuotas en el año; la primera a más tardar el último día del mes de junio y la segunda durante los primeros 20 días del mes de diciembre.

    h3 Vacaciones
    p.mb-5 Corresponden a 15 días hábiles de descanso remunerado por cada año laborado, o proporcional por fracción de año si el tiempo laborado es inferior a un año (Prestaciones sociales, s.f., p. 1).
    separador
    #t_2_3.titulo-segundo
      h2 2.3 Liquidación de la nómina
    p Para liquidar de manera adecuada la nómina de producción se debe tener en cuenta el inciso primero del artículo 114-1 del Estatuto Tributario: 
    .row.justify-content-around.align-items-center
      .col-lg-11
        .bloque-texto-d.color-secundario.p-4.mb-5.aaa 
            .bloque-texto-d__texto.mb-2
              i.fas.fa-quote-left
              h3.text-regular Estarán exoneradas del pago de los aportes parafiscales a favor del Servicio Nacional de Aprendizaje (SENA), del Instituto Colombiano de Bienestar Familiar (ICBF) y las cotizaciones al Régimen Contributivo de Salud, las sociedades y personas jurídicas y asimiladas contribuyentes declarantes del impuesto sobre la renta y complementarios, correspondientes a los trabajadores que devenguen, individualmente considerados, menos de diez (10) salarios mínimos mensuales legales vigentes. 

            .bloque-texto-d__autor 
              .h5.mb-0 Estatuto Tributario Nacional, art. 114. 
                i.fas.fa-quote-right    

    p Inciso segundo del artículo 114-1 del Estatuto Tributario: 
    .row.justify-content-around.align-items-center  
      .col-lg.justify-content-md-center.align-self-center
        .bloque-texto-d.color-secundario.p-4.mb-5.aaa 
            .bloque-texto-d__texto.mb-2
              i.fas.fa-quote-left
              h3.text-regular Así mismo las personas naturales empleadoras estarán exoneradas de la obligación de pago de los aportes parafiscales al SENA, al ICBF y al Sistema de Seguridad Social en Salud por los empleados que devenguen menos de diez (10) salarios mínimos legales mensuales vigentes. Lo anterior no aplicará para personas naturales que empleen menos de dos trabajadores, los cuales seguirán obligados a efectuar los aportes de que trata este inciso.

            .bloque-texto-d__autor 
              .h5.mb-0 Estatuto Tributario Nacional, art. 114. 
                i.fas.fa-quote-right   
      .col-12.col-lg-auto.justify-content-md-center.mb-4 
        figure.mb-5
          img.img-450.mb-2(src="@/assets/tema2/img-16.svg")               

    .bloque-texto-d.color-secundario.p-4.mb-5.aaa 
      .bloque-texto-d__texto.mb-2
        i.fas.fa-quote-left
        h3.text-regular Los contribuyentes que opten por acogerse al impuesto unificado bajo el régimen simple de tributación - SIMPLE, deberán realizar los respectivos aportes al Sistema General de Pensiones de conformidad con la legislación vigente y estarán exonerados de aportes parafiscales en los términos del artículo 114-1 del Estatuto Tributario.
      .bloque-texto-d__autor 
        .h5.mb-0 El parágrafo 3 del artículo 903 del Estatuto Tributario Nacional, art. 114. 
        i.fas.fa-quote-right 

    p Además, el Decreto 1174 de 1991, artículo 1°. El salario integral a que se refiere el numeral 2° del artículo 132 del Código Sustantivo del Trabajo, modificado por el artículo 18 de la Ley 50 de 1990, será una sola suma convenida libremente y por escrito entre el trabajador y el empleador, suma que será la base para las cotizaciones del Instituto de Seguros Sociales, la liquidación de las indemnizaciones a que se refiere el artículo 64 del Código Sustantivo del Trabajo y la remuneración por vacaciones (Gerencie, 2020).
    p.mb-5 Lo anterior, corresponde al proceso mediante el cual se determinan el devengo, deducciones y neto a pagar al colaborador. Además, se tiene en cuenta apropiaciones con el fin de realizar la respectiva provisión de acuerdo con el periodo de pago y políticas establecidas para el área de producción.
         
    h3 Elementos en la liquidación de nómina
    .row.justify-content-around.align-items-center.px-5  
      .col-12.col-lg-auto.justify-content-md-center.mb-4.px-5  
        figure.mb-5
          img.img-450.mb-2(src="@/assets/tema2/img-17.png")  
      .col-lg.justify-content-md-center.align-self-center.px-5 
        .ul.lista-ul--color
              li 
                i #[span.square 1] 
                p.mb-4 Devengados.
              li 
                i #[span.square 2] 
                p.mb-4 Deducciones.
              li 
                i #[span.square 3] 
                p.mb-4 Neto a pagar.
              li 
                i #[span.square 4] 
                p.mb-4 Aportes parafiscales y seguridad social.
              li 
                i #[span.square 5] 
                p.mb-5 Prestaciones sociales.

    h3 Fases y liquidación de nómina 
    LineaTiempoD.color-acento-contenido.mb-5
      .row.fond7(numero="1" titulo="Devengado")
        .col-md-6
          figure
            img.img-250.mb-2(src="@/assets/tema2/img-18.svg")
          

        .col-md-6.mb-4.mb-md-0
          p Se debe liquidar y relacionar cada concepto por separado correspondiente a lo ganado y al tiempo laborado.
          .ul.lista-ul--color
            li 
              i.ch.fas.fa-check
              p Sueldo básico devengado = sueldo básico concertado entre las partes dividido en 30 multiplicado por días trabajados.
            li 
              i.ch.fas.fa-check
              p Auxilio de transporte devengado = auxilio transporte vigente dividido en 30 multiplicado por días trabajados.
            li 
              i.ch.fas.fa-check
              p Demás conceptos, liquidados previamente.

      
        

      .row(numero="2" titulo="Deducciones")
        .col-md-6
          figure
            img.img-250.mb-2(src="@/assets/tema2/img-19.png")
           
        .col-md-6.mb-4.mb-md-0
          p Se debe liquidar y relacionar cada concepto por separado correspondiente a lo descontado (salud, pensión, retención en la fuente, otros descuentos).
          .ul.lista-ul--color
            li 
              i.ch.fas.fa-check
              p #[strong Salud] = Ingreso base de cotización “IBC” (total devengado menos auxilio de transporte) multiplicado por porcentaje vigente para el trabajador (4% 2020). 
            li 
              i.ch.fas.fa-check
              p #[strong Pensión ]= Ingreso base de cotización “IBC” (total devengado menos auxilio de transporte) multiplicado por porcentaje vigente para el trabajador (4% 2020). 
            li 
              i.ch.fas.fa-check
              p #[strong Fondo de solidaridad pensional] = Ingreso base de cotización “IBC” (total devengado menos auxilio de transporte) multiplicado por porcentaje vigente para el trabajador, a partir de 4 salarios mínimos vigentes. 
            li 
              i.ch.fas.fa-check
              p #[strong Retención en la fuente]. Según previa liquidación.

      

      .row(numero="3" titulo="Neto a pagar")
        .col-md-6
          figure
            img.img-250.mb-2(src="@/assets/tema2/img-20.svg")
            

        .col-md-6.mb-4.mb-md-0.justify-content-md-center.align-self-center
          p Según la liquidación de cada trabajador se dispone a restar el total de deducciones al total devengado

      .row(numero="4" titulo="Aportes parafiscales y seguridad social")
        .col-md-6
          figure
            img.img-250.mb-2(src="@/assets/tema2/img-21.png")
           
        .col-md-6.mb-4.mb-md-0
          p Teniendo en cuenta el ingreso base de cotización “IBC” se calculará los siguientes aportes, que debe realizar el empleador:
          .ul.lista-ul--color
            li 
              i.ch.fas.fa-check
              p SENA 2% (revisar exoneración).
            li 
              i.ch.fas.fa-check
              p ICBF 3% (revisar exoneración).
            li 
              i.ch.fas.fa-check
              p Caja de compensación 4%.
            li 
              i.ch.fas.fa-check
              p Salud 8,5% (revisar exoneración).
            li 
              i.ch.fas.fa-check
              p ARL (según riesgo de cada trabajador).
            li 
              i.ch.fas.fa-check
              p Pensión 12%.

      .row(numero="5" titulo="Prestaciones sociales")
        .col-md-6
          figure
            img.img-250.mb-2(src="@/assets/tema2/img-22.svg")
            

        .col-md-6.mb-4.mb-md-0
          p Teniendo en cuenta el total devengado de cada trabajador, se liquidará el valor de la provisión a cada una de las prestaciones o beneficios a empleados.    
          .ul.lista-ul--color
            li 
              i.ch.fas.fa-check
              p Cesantías = Total devengado x 8,33%.
            li 
              i.ch.fas.fa-check
              p Intereses sobre cesantías = Total devengado x 1%.
            li 
              i.ch.fas.fa-check
              p Prima de servicios = Total devengado x 8,33%.
            li 
              i.ch.fas.fa-check
              p Vacaciones = Total devengado x 4,17%.

    p A continuación, se refleja la contabilización de la nómina de producción:  
    .tabla-b.color-acento-contenido.mb-5.px-5      
      table
        tbody
          tr.tb-h
            th.r-r  C&oacute;digo 
            th.r-r  Cuenta 
            th.r-r  D&eacute;bitos 
            th.r-r  Cr&eacute;dito 
        
          tr
            td.text-center
              b 720506 
            td.b-c  Sueldos 
            td.b-c.t-r  $828.116,00 
            td    
          tr
            td.text-center
              b 720527 
            td.b-c  Auxilio de transporte 
            td.b-c.t-r  $91.032,00 
            td    
          tr
            td.text-center
              b 720530 
            td.b-c  Cesant&iacute;as 
            td.b-c.t-r  $76.565,00 
            td    
          tr
            td.text-center
              b 720533 
            td.b-c  Intereses de cesant&iacute;as 
            td.b-c.t-r  $9.187,00 
            td    
          tr
            td.text-center
              b 720536 
            td.b-c  Prima de servicios 
            td.b-c.t-r  $76.565,00 
            td    
          tr
            td.text-center
              b 720539 
            td.b-c  Vacaciones 
            td.b-c.t-r  $34.532,00 
            td    
          tr
            td.text-center
              b 720568 
            td.b-c  Aportes a administradores de riesgos profesionales 
            td.b-c.t-r  $4.322,00 
            td    
          tr
            td.text-center
              b 720570 
            td.b-c  Aportes de fondos de pensiones 
            td.b-c.t-r  $99.373,00 
            td    
          tr
            td.text-center
              b 720572 
            td.b-c  Aportes cajas de compensaci&oacute;n familiar 
            td.b-c.t-r  $33.124,00 
            td    
          tr
            td.text-center
              b 237005 
            td.b-c  Aportes a entidades promotoras de salud EPS 
            td.b-c    
            td.t-r  $33.124,00 
          tr
            td.text-center
              b 237006 
            td.b-c  Aportes a administradores de riesgos profesionales 
            td.b-c    
            td.t-r  $4.322,00 
          tr
            td.text-center
              b 237010 
            td.b-c  Aportes al I.C.B.F, SENA y cajas de compensaci&oacute;n 
            td.b-c    
            td.t-r  $33.124,00 
          tr
            td.text-center
              b 238030 
            td.b-c  Fondos de cesant&iacute;as y/o pensiones 
            td.b-c    
            td.t-r  $132.498,00 
          tr
            td.text-center
              b 261005 
            td.b-c  Cesant&iacute;as 
            td.b-c    
            td.t-r  $76.565,00 
          tr
            td.text-center
              b 261010 
            td.b-c  Intereses sobre cesant&iacute;as 
            td.b-c    
            td.t-r  $9.187,00 
          tr
            td.text-center
              b 261015 
            td.b-c  Vacaciones 
            td.b-c    
            td.t-r  $34.532,00 
          tr
            td.text-center
              b 261020 
            td.b-c  Prima de servicios 
            td.b-c    
            td.t-r  $76.565,00 
          tr
            td.text-center
              b 250501 
            td.b-c  Empleados 
            td.b-c    
            td.t-r  $852.899,00 
          tr
            td.text-center(colspan='2')
              b  SUMAS IGUALES 
            td.b-c.t-r  
              b $1.252.816,00 
            td.t-r
              b  $1.252.816,00 




    p Es importante explorar las páginas sugeridas y la biblioteca SENA para ampliar los conocimientos en cuanto al tema.      
        




</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    datosLineaTiempoB: [
      {
        titulo: 'Hora extraordinaria diurna “HEOD”',
        texto:
          'La hora extra diurna es la que se labora luego de la jornada laboral, y entre las 6 de la mañana y las 9 de la noche.',
        icono: require('@/assets/tema2/img-5.svg'),
      },
      {
        titulo: 'Hora extraordinaria nocturna “HEON”',
        texto:
          'La hora extra nocturna es la que se labora luego de la jornada laboral, y entre las 9 de la noche y las 6 de la mañana.',
        icono: require('@/assets/tema2/img-6.svg'),
      },
      {
        titulo: 'Hora dominical y festivo diurna',
        texto:
          'Se presenta durante la jornada ordinaria que se labora el domingo o festivo y entre las 6 de la mañana y las 9 de la noche.',
        icono: require('@/assets/tema2/img-7.svg'),
      },
      {
        titulo: 'Hora dominical y festivo nocturna',
        texto:
          'Se presenta durante la jornada ordinaria que se labora el domingo o festivo, entre las 9 de la noche y las 6 de la mañana.',
        icono: require('@/assets/tema2/img-8.svg'),
      },
      {
        titulo: 'Hora extra dominical diurna “HEDD”',
        texto:
          'La hora extra dominical diurna es la que se labora luego de la jornada laboral, y entre las 6 de la mañana y las 9 de la noche; siempre y cuando se trabaje en un domingo o festivo y, se trabajen más de 8 horas diarias si esa es la jornada ordinaria.',
        icono: require('@/assets/tema2/img-9.svg'),
      },
      {
        titulo: 'Hora extra-dominical nocturna “HEDN”',
        texto:
          'La hora extra dominical nocturna es la que se labora luego de la jornada laboral, entre las 9 de la noche y las 6 de la mañana, cuando se labora domingo o festivo. ',
        icono: require('@/assets/tema2/img-10.svg'),
      },
      {
        titulo: 'Recargo nocturno',
        texto:
          'El numeral 1 del artículo 168 del Código Sustantivo del Trabajo señala que el trabajo nocturno se remunera con un recargo del 35%.',
        icono: require('@/assets/tema2/img-11.svg'),
      },
    ],
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

<style lang="sass" scoped></style>
