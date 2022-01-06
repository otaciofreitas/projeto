<template>
<div class="formulario">
  <h3>Formulário Inicial</h3>
  <form>
  <div class="mb-3">
    <div class="row">
  <div class="col">
    <label for="exampleInputEmail1" class="form-label">Nome</label>
    <input type="text" class="form-control"  aria-label="First name">
  </div>
  <div class="col">
    <label for="exampleInputEmail1" class="form-label">Sobrenome</label>
    <input type="text" class="form-control" aria-label="Last name"><br>
  </div>
</div>
    <label for="exampleInputEmail1" class="form-label">Endereço de Email</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
    <div id="emailHelp" class="form-text">Você irá receber um email de confirmação</div>
  </div>
  <div class="mb-3">
    <label for="exampleInputPassword1" class="form-label">Senha</label>
    <input type="password" class="form-control" id="exampleInputPassword1">
  </div>
  <div class="mb-3 form-check">
    <input type="checkbox" class="form-check-input" id="exampleCheck1">
    <label class="form-check-label" for="exampleCheck1">Salvar Senha</label>
  </div>
  <div class="mb-3">
  <label for="formFile" class="form-label">Adicionar Arquivo</label>
  <input class="form-control" type="file" id="formFile">
</div>
<div class="input-group mb-3">
  <input type="file" class="form-control" id="inputGroupFile02">
  <label class="input-group-text" for="inputGroupFile02">Enviar uma Foto</label>
</div>
  <button type="submit" class="btn btn-primary">Enviar Informações</button>
  
</form>
  </div>
</template>

<script>
export default {
  name: 'Formulario'
}
  </script>

<style>
.formulario {
  padding: 20px;
  width: 500px;
  background: rgb(219, 219, 219);
  margin: 30px;
}

</style>