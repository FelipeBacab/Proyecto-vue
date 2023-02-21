<script setup>
import Elementos from './Elementos.vue'
</script>

<template>


  <Elementos>
    
    <template #heading>Sitio Web</template>

    Los sitios web son lo que conocemos comúnmente por "página web".

    Es la solución adecuada para:

    <ul>
      <li type="square">Promover servicios o productos.</li>
      <li type="square">Presentar contenidos o información al público.</li>
      <li type="square">Promover un negocio.</li>
    </ul>
    <br />
    <CENTER>
    <img src="https://conocimientolibre.mx/wp-content/uploads/2019/06/sitios-web.png" alt="sitio web" class="w-36 float-left mr-5" width="400" height="300">
    </CENTER>
  </Elementos>

   <Elementos>
    
    <template #heading>Aplicación Web</template>

    Son como los sitios web, pero estos además pueden manipular datos.

    Es la solución adecuada para:

    <ul>
      <li type="square">Registrar usuarios.</li>
      <li type="square">Mostrar información que cambia con el tiempo.</li>
      <li type="square">Realizar cálculos con información de los usuarios.</li>
    </ul>
    <br />
    <CENTER>
    <img src="https://th.bing.com/th/id/R.8d13df8855f8084e4444c8df2d743cbf?rik=hGfMyQ0IYsIqag&pid=ImgRaw&r=0" alt="sitio web" class="w-36 float-left mr-5" width="400" height="300">
    </CENTER>
  </Elementos>
</template>

<style scoped>
 
  background: #000000;
</style>
