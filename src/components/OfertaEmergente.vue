<template>
  <div class="OfertaEmergente" style="background-color: #cf2d3e;">
   <p id="msgfashion">Aprovecha Hot Fashion del 12 al 19 de agosto</p>
    <a href="" id="botonOfer" role="button">Ver ofertas</a>

  </div>
</template>

<script>
export default {
  name: 'OfertaEmergente',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.OfertaEmergente{
  
  display: flex;
  font-size: small;
  justify-content: center;
}
p{
  color: #ffffff;
}

a{
 
  background-color: #ffffff;
  border: none;
  color: #000000;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 1.5%;
  padding-right: 1.5%;
  text-decoration: none;
  font-size: 80%;
  border-radius: 15px;
}
</style>
