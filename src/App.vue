<template>
  <div id="app">
    <div id="imagem"><div class="imagem"><img alt="Vue logo" src="./assets/logo.png">
    </div>
    </div>
    <div>
      <HelloWorld/>
      <Inicio/>
      <Formulario/>
      <Rodape/>


    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Rodape from './components/rodape.vue'
import Inicio from './components/Inicio.vue'
import Formulario from './components/Formulario.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Rodape,
    Inicio,
    Formulario
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
#imagem {
  padding: 30px;
  background: rgb(241, 241, 250);
}

</style>
