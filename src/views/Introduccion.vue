<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.justify-content-around.align-items-center
      .col-8
        figure.mb-5
          img(src='@/assets/tema1/img-intro.svg', alt='Marketing')
    
    p Durante el recorrido por este componente se fortalecerá el conocimiento sobre las generalidades de costos, su importancia, elementos, clasificación y normatividad, así como la temática de la nómina en empresas industriales, lo anterior permite adquirir mayores herramientas para enfrentarse al mundo contable y poner en práctica los conocimientos adquiridos. 

    p #[strong Notas aclaratorias:] las tablas que se toman como referencia en los ejemplos en cada uno de los temas desarrollados, elaboradas mediante el programa Excel, son derivadas de los mismos, por lo tanto no se numeran y la elaboración es propia salvo donde se indique lo contrario.

    p Además, para la elaboración de este apartado se abordaron diversas fuentes de conceptos de gestión contable e información financiera las que se han citado y referenciado para los fines educativos de esta materia en el entendido que el conocimiento es social y, por lo tanto, es para usarlo por quienes necesitan adquirirlo. Se espera que este documento sea útil para todos, aprendices y lectores en general. 



</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
