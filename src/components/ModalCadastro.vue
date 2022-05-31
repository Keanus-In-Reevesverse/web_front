<template>
  <div class="modalCadastro">
    <!-- Modelo Modal Cadastro -->
    <section class="modal fade" id="register-modal" tabindex="-1" aria-labelledby="exampleModalLabel"
      aria-hidden="true">
      <div class="modal-dialog">
        <dialog class="modal-content">
          <header class="modal-header">
            <h5 class="modal-title" id="exampleModalLabel">Cadastro</h5>
            <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
          </header>
          <main class="modal-body">
            <!--fomulario de cadastro -->
            <form>
              <!--<div class="mb-3">
                    <label for="InputName" class="form-label">Nome</label>
                    <input type="text" class="form-control" id="InputName">
                </div>-->
              <div class="mb-3">
                <label for="InputEmail" class="form-label">E-mail</label>
                <input type="email" class="form-control" id="InputEmail" placeholder="Insira o e-mail">
              </div>
              <div class="mb-3">
                <label for="InputCel" class="form-label">Celular</label>
                <input type="text" class="form-control" id="InputCel"
                  placeholder="Insira seu numero de celular (Opcional)">
              </div>

              <label for="InputPassword1" class="form-label">Senha</label>

              <div class="input-group mb-3 align-items-center">
                <input type="password" class="form-control" id="InputPassword1" placeholder="Insira a senha">
                <div>
                  <input type="checkbox" class="form-check-input-in-line mx-2" id="checkBoxP">
                  <label class="form-check-label" for="checkBoxP">Visualizar senha</label>
                </div>
              </div>

              <label for="InputPassword2" class="form-label">Confirmar senha</label>

              <div class="input-group mb-3 align-items-center">
                <input type="password" class="form-control" id="InputPassword2" placeholder="Confirme a senha">
                <div>
                  <input type="checkbox" class="form-check-input-in-line mx-2" id="checkBoxCP">
                  <label class="form-check-label" for="checkBoxCP">Visualizar senha</label>
                </div>
              </div>
              <button type="submit" class="btn btn-success">Registrar</button>
            </form>
            <!--final do fomulario de login -->
          </main>
          <footer class="modal-footer">
            <button type="button" class="btn btn-outline-success" data-bs-toggle="modal"
              data-bs-target="#login-modal">Ja possui uma conta?</button>
          </footer>
        </dialog>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'ModalCadastro',
  props: {

  }
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
  color: #42b983;
}
</style>
