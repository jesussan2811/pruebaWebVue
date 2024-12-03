<template>
<nav class="navbar navbar-Yellow" style="background-color: #ffdd30;">
  <div class="container-fluid">

    <div class="d-flex">

        <a class="navbar-brand" href="#">
          <img src="../assets/logo-coppel.png" class = "logo" alt="Logo Coppel" />
        </a>

      <div class="ms-auto m-0">
      <form class="d-flex">
        <input class="form-control ms-2" type="search" placeholder="Busca tus productos" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
            <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001q.044.06.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1 1 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0"/>
          </svg>
        </button>
      </form>
    </div>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">
            <div>
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-telephone-fill" viewBox="0 0 16 16">
              <path fill-rule="evenodd" d="M1.885.511a1.745 1.745 0 0 1 2.61.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.68.68 0 0 0 .178.643l2.457 2.457a.68.68 0 0 0 .644.178l2.189-.547a1.75 1.75 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.6 18.6 0 0 1-7.01-4.42 18.6 18.6 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877z"/></svg>
              <p class="sin_subrraya">Compra ahora</p>
              <p>800 220 7735</p>
            </div>
          </a>
        </li>

        <li class="nav-item dropdown">
          <a class="btn btn-secondary dropdown-toggle" href="#" role="button" id="dropdownMenuLink" data-bs-toggle="dropdown" aria-expanded="false">
            Inicia sesion
          </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="#">Iniciar sesion</a></li>
              <li><a class="dropdown-item" href="#">Crear cuenta</a></li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </div>
</nav>
</template>

<script>
export default {
  name: 'Navbar',
};
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.logo{
    width: 20%;
    height: auto;
}

</style>
