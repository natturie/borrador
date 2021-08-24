<template>
  <div class="home">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <div class="inicio">
      <div class="formulario">
      <h1 class="tituloInicio">Sierra Café</h1>
      <h3 class="eslogan">De las montañas a tu mesa</h3>
      <button class="btnIngreso"><a>Ingresar</a></button>
      <button class="btnRegistro"><a>Registro</a></button>
    </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

// export default {
//   name: 'Home',
//   components: {
//     HelloWorld
//   }
// }
</script>

<style scoped> 
.home{
    background: url('../assets/wallpapercafe.jpg');
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: cover;
    /* font-family: 'Lexend Deca', sans-serif;  
    font-weight: lighter; */
    font-family: 'Lexend', sans-serif;
    /* display: flex;
    flex-direction: column; */
}

.inicio{
    display: flex;
    flex-direction: column;
    align-content: center;
    align-items: center;
    color: white;
    width: 40%;   
}

.formulario{
  margin: 108px 100px;
}

.tituloInicio{
    font-size: 64px;
}

.eslogan{
    font-size: 24px;
}

.btnIngreso, .btnRegistro{
    font-size: 22px;
    width: 300px;
    height: 45px;
    background: #306966;
    color: white;
    border-radius: 40px;
    margin: 10px 0;
    border-width: 0;
}
</style>
