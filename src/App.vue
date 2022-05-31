<template>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    

  <body class="background-color-custom">

    <!--cabeçalho -->
    <!--<header class="header container-fluid bg-secondary"> -->

    <header>
    </header>

    <main class="container-fluid">

      <!--nav bar -->
      <!--EM AJUSTE-->
      <section>
        <nav class="border navbar navbar-expand-lg navbar-light bg-light fixed-top">
          <div class="container-fluid">
            <!--Icon/Home-->
            <a class="navbar-brand fonte-ubuntu" href="#">Home</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
              aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <!--Posição dos buttons-->
            <!--EM AJUSTE-->
            <div class="collapse navbar-collapse justify-content-around" id="navbarNav">
              <ul class="navbar-nav ">
                <!--DropDown_list 01-->
                <li class="nav-item dropdown">
                  <!--aria-current="page"-->
                  <a class="nav-link dropdown-toggle" aria-current="page" href="#" id="navbarDropdown" role="button"
                    data-bs-toggle="dropdown" aria-expanded="false">
                    Popular</a>
                  <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                    <li><a class="dropdown-item" href="#">Action</a></li>
                    <li><a class="dropdown-item" href="#">Another action</a></li>
                    <li><a class="dropdown-item" href="#">Something else here</a></li>
                  </ul>
                </li>
                <!--DropDown_list 02-->
                <li class="nav-item dropdown">
                  <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                    data-bs-toggle="dropdown" aria-expanded="false">
                    Novidades</a>
                  <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                    <li><a class="dropdown-item" href="#">Action</a></li>
                    <li><a class="dropdown-item" href="#">Another action</a></li>
                    <li><a class="dropdown-item" href="#">Something else here</a></li>
                  </ul>
                </li>
                <!--DropDown_List 03-->
                <li class="nav-item dropdown">
                  <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                    data-bs-toggle="dropdown" aria-expanded="false">
                    Promoções</a>
                  <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                    <li><a class="dropdown-item" href="#">Action</a></li>
                    <li><a class="dropdown-item" href="#">Another action</a></li>
                    <li><a class="dropdown-item" href="#">Something else here</a></li>
                  </ul>
                </li>
                <!--DropDown_List 04-->
                <li class="nav-item dropdown">
                  <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                    data-bs-toggle="dropdown" aria-expanded="false">
                    Gêneros</a>
                  <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                    <li><a class="dropdown-item" href="#">Action</a></li>
                    <li><a class="dropdown-item" href="#">Another action</a></li>
                    <li><a class="dropdown-item" href="#">Something else here</a></li>
                  </ul>
                </li>
              </ul>
              <!--Search-->
              <form class="d-flex">
                <input class="form-control me-2" type="search" placeholder="Pesquise" aria-label="Search">
                <button class="btn btn-outline-success" type="submit">Pesquisar</button>
              </form>
              <!--Botao Login e Cadastro-->
              <form class="d-flex gap-2 justify-content-md-end">
                <button type="button" class="btn btn-success" data-bs-toggle="modal" data-bs-target="#login-modal"
                  aria-expanded="false">Login</button>
                <button type="button" class="btn btn-outline-success" data-bs-toggle="modal"
                  data-bs-target="#register-modal" aria-expanded="false">Cadastrar</button>
              </form>
            </div>
          </div>
        </nav>
      </section>


      <!--carrosel -->
      <!--EM AJUSTE-->
      <section id="carouselExampleCaptions" class="carousel slide" data-bs-interval="2650" data-bs-ride="carousel">
        <div class="carousel-indicators">
          <!--Botoes inferiores-->
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
            aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
            aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
            aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <!--1 imagem -->
          <div class="carousel-item active">
            <img src="./assets/01.jpg" class="d-block w-100 imagem-carrosel" alt="...">
            <div class="carousel-caption d-none d-md-block  cor-carrosel">
              <h5>First slide label</h5>
            </div>
          </div>
          <!--2 imagem -->
          <div class="carousel-item">
            <img src="./assets/02.jpg" class="d-block w-100 imagem-carrosel" alt="...">
            <div class="carousel-caption d-none d-md-block  cor-carrosel">
              <h5>Second slide label</h5>
            </div>
          </div>
          <!--3 imagem -->
          <div class="carousel-item">
            <img src="./assets/03.jpg" class="d-block w-100 imagem-carrosel" alt="...">
            <div class="carousel-caption d-none d-md-block  cor-carrosel">
              <h5>Third slide label</h5>
            </div>
          </div>
        </div>
        <!--Botao seta prev-->
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions"
          data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <!--Botao seta next-->
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions"
          data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </section>

      <!--Texto -->
      <section class="container-fluid bg-light" id="titulo">
        <h1 class="text-center pt-3">Título</h1>
        <h3 class="text-center text-secondary pb-0"> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
          exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</h3>
        <h3 class="text-center text-secondary pb-5"> Lorem ipsum dolor sit amet, consectetur adipiscing elit,
          sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
          nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.Lorem ipsum dolor sit
          amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
          Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
          consequat</h3>
      </section>

      <!--cards-->
      <!--EM AJUSTE-->
      <!--Ajustar o Grid-->
      <section class="container-fluid bg-light" id="cards">
        <div class="row justify-content-center">
          <!--01 Item-->
          <article class="card borda-cards-color card-largura p-0 m-5 col-md-4 col-12">
            <img src="./assets/01.jpg" class="card-img-top posição-card-imagem" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <h6 class="card-text">Some quick example text to build on the card title and make up the bulk of the
                card's content.</h6>
              <!-- botão cards-->
              <a href="#" class="btn btn-primary">Veja mais</a>
            </div>
          </article>
          <!--02 Item-->
          <article class="card borda-cards-color card-largura p-0 m-5 col-md-4 col-12">
            <img src="./assets/02.jpg" class="card-img-top posição-card-imagem" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <h6 class="card-text">Some quick example text to build on the card title and make up the bulk of the
                card's content.</h6>
              <!-- botão cards-->
              <a href="#" class="btn btn-primary">Veja mais</a>
            </div>
          </article>
          <!--03 Item-->
          <article class="card borda-cards-color card-largura p-0 m-5 col-md-4 col-12">
            <img src="./assets/03.jpg" class="card-img-top posição-card-imagem" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <h6 class="card-text">Some quick example text to build on the card title and make up the bulk of the
                card's content.</h6>
              <!-- botão cards-->
              <a href="#" class="btn btn-primary">Veja mais</a>
            </div>
          </article>
          <!--04 Item-->
          <article class="card borda-cards-color card-largura p-0 m-5 col-md-4 col-12">
            <img src="./assets/04.jpg" class="card-img-top posição-card-imagem" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <h6 class="card-text">Some quick example text to build on the card title and make up the bulk of the
                card's content.</h6>
              <!-- botão cards-->
              <a href="#" class="btn btn-primary">Veja mais</a>
            </div>
          </article>
        </div>
      </section>

    </main>

    <footer class="footer">
      <p class=" text-center "> informações de rodape
      </p>
    </footer>
  </body>

</template>

<script>
//import ModalCadastro from './components/ModalCadastro.vue'
//import ModalCadastro from './components/ModalCadastro.vue'

export default {
  name: 'App',
  components: {
    //ModalCadastro,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
