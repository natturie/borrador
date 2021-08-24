<template>
  <div class="login">
    <formulario-inicio msg="Ingresar"/> 
    <form class="entrada">
        <input type="email">
        <input type="password">

    </form>
  </div>
</template>

<script>
//  @ is an alias to /src
import FormularioInicio from '../components/FormularioInicio.vue'

 export default {
   name: 'FormularioLogin',
   components: {
     FormularioInicio
   }
 }
</script>

<style>

</style>


      