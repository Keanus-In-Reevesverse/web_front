<template>
  <div class="modalLogin">
  <!-- Modelo Modal Login -->
  <section class="modal fade" id="login-modal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog">
      <dialog class="modal-content">
        <header class="modal-header">
          <h5 class="modal-title" id="exampleModalLabel">Login</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </header>
        <main class="modal-body">
          <!--fomulario de login -->
          <form>
            <div class="mb-3">
              <label for="InputEmailLogin" class="form-label">E-mail</label>
              <input type="email" class="form-control" id="InputEmailLogin" aria-describedby="emailHelp"
                placeholder="Insira o e-mail">
              <div id="emailHelp" class="form-text">Nunca iremos compartilhar seu e-mail com outra pessoa.</div>
            </div>
            <div class="mb-3">
              <label for="InputPasswordLogin" class="form-label">Senha</label>
              <input type="password" class="form-control" id="InputPasswordLogin" placeholder="insira a senha">
            </div>
            <div class="mb-3 form-check">
              <input type="checkbox" class="form-check-input" id="exampleCheck1">
              <label class="form-check-label" for="exampleCheck1">Manter conectado</label>
            </div>
            <button type="submit" class="btn btn-success">Logar</button>
          </form>
          <!--final do fomulario de login -->
        </main>
        <footer class="modal-footer">
          <button type="button" class="btn btn-light">Esqueceu a senha?</button>
          <button type="button" class="btn btn-outline-success" data-bs-toggle="modal"
            data-bs-target="#register-modal">Cadastrar</button>
        </footer>
      </dialog>
    </div>
  </section>
  </div>
</template>

<script>
export default {
  name: 'ModalLogin',
  props: {

  }
}
</script>