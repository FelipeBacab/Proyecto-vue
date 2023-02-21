<script setup>
import Inicio from './components/Inicio.vue'
import Primeras from './components/Primeras_preguntas.vue'
import Ultimas from './components/Ultimas_preguntas.vue'
import Tipos from './components/Tipo_programa.vue'
import Galeria from './components/Galeria.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" />

    <div class="wrapper">
      <Inicio msg=" " />
    </div>
  </header>


  <main>
    <Primeras />
    <Ultimas />
    <Tipos />
    <Galeria />
  </main>

  <footer>
      Contáctanos
      <img src="http://isclab.com.mx/img/svg/email.svg" alt="email" class="w-6 h-6" width="30" height="20" />
      Email: contacto@isclab.com.mx
  </footer>

</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
