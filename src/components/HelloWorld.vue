<template>
  <div class="hello">
    <div>
  <b-navbar class="barra" type="black" variant="blue">
    <b-navbar-nav>
      <b-nav-item href="www.google.com.br">Início</b-nav-item>
      <b-nav-item href="Verformularios.vue">Formulários</b-nav-item>
      <b-nav-item href="#">Informações</b-nav-item>
      <b-nav-item href="#">Edição</b-nav-item>


      <!-- Navbar dropdowns -->
      <b-nav-item-dropdown text="Banco de Dados" right>
        <b-dropdown-item href="#">Lista de Clientes</b-dropdown-item>
        <b-dropdown-item href="#">Lista de Empresas</b-dropdown-item>
      </b-nav-item-dropdown>

      <b-nav-item-dropdown text="Usuário" right>
        <b-dropdown-item href="#">Conta</b-dropdown-item>
        <b-dropdown-item href="#">Configurações</b-dropdown-item>
        <b-dropdown-item href="#">Sair</b-dropdown-item>
      </b-nav-item-dropdown>
    </b-navbar-nav>
  </b-navbar>
  
</div>
  
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #4346fd;
}
.barra{
  background: #dbdbf7;
}
</style>
