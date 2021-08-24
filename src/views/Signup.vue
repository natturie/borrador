<template>
  <div class="signup">
    <formulario-inicio msg="Registro"/> 
  </div>
</template>

<script>
//  @ is an alias to /src
import FormularioInicio from '../components/FormularioInicio.vue'

 export default {
   name: 'FormularioSignup',
   components: {
     FormularioInicio
   }
 }
</script>