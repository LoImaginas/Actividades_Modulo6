<script setup>
import chefcitoImg from './assets/img/chefcito.png'
import dulcesImg from './assets/img/dulces.jpg'
import bebidasImg from './assets/img/bebidas.jpg'
import colacionesImg from './assets/img/colaciones.jpg'
import desayunosImg from './assets/img/desayunos.jpg'
import empanadasImg from './assets/img/empanadas.jpg'
import verdurasImg from './assets/img/verduras.jpg'

const logoSrc = chefcitoImg
</script>

<template>
  <nav class="navbar navbar-expand-lg bg-azulito" data-bs-theme="dark">
    <div class="container">
      <a class="navbar-brand col-2" href="#">
        <img class="logo-chefcito" :src="logoSrc" alt="logo-chefcito" />
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav ms-auto">
          <a class="nav-link active fs-3" aria-current="page" href="#">Inicio</a>
          <a class="nav-link fs-3" href="#">Nuestros Platos</a>
          <a class="nav-link fs-3" href="#">Contacto</a>
        </div>
      </div>
    </div>
  </nav>

  <header class="container">
    <h1 class="text-center my-5 display-1 fw-medium text-primary-emphasis">Restaurantcito</h1>
  </header>

  <section class="container mb-5">
    <h2 class="text-center my-5 display-5 fw-normal">Nuestros Platos</h2>
    <div class="row gap-5 justify-content-evenly">
      <div class="card col-10 col-sm-10 col-md-5 col-lg-3 p-0">
        <img :src="bebidasImg" class="card-img-top" alt="..." />
        <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">
            Some quick example text to build on the card title and make up the bulk of the card's
            content.
          </p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
      </div>
      <div class="card col-10 col-sm-10 col-md-5 col-lg-3 p-0">
        <img :src="colacionesImg" class="card-img-top" alt="..." />
        <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">
            Some quick example text to build on the card title and make up the bulk of the card's
            content.
          </p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
      </div>
      <div class="card col-10 col-sm-10 col-md-5 col-lg-3 p-0">
        <img :src="desayunosImg" class="card-img-top" alt="..." />
        <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">
            Some quick example text to build on the card title and make up the bulk of the card's
            content.
          </p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
      </div>
      <div class="card col-10 col-sm-10 col-md-5 col-lg-3 p-0">
        <img :src="dulcesImg" class="card-img-top" alt="..." />
        <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">
            Some quick example text to build on the card title and make up the bulk of the card's
            content.
          </p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
      </div>
      <div class="card col-10 col-sm-10 col-md-5 col-lg-3 p-0">
        <img :src="empanadasImg" class="card-img-top" alt="..." />
        <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">
            Some quick example text to build on the card title and make up the bulk of the card's
            content.
          </p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
      </div>
      <div class="card col-10 col-sm-10 col-md-5 col-lg-3 p-0">
        <img :src="verdurasImg" class="card-img-top" alt="..." />
        <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">
            Some quick example text to build on the card title and make up the bulk of the card's
            content.
          </p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
      </div>
    </div>
  </section>

  <section class="py-5 bg-azulito text-white d-none d-lg-block">
    <div class="container d-flex justify-content-between py-5">
      <h2 class="display-5 fw-medium">Medios de Pago</h2>
      <div class="d-flex gap-5">
        <i class="fa-brands fa-cc-visa fa-4x"></i>
        <i class="fa-brands fa-cc-mastercard fa-4x"></i>
        <i class="fa-brands fa-cc-amex fa-4x"></i>
        <i class="fa-brands fa-cc-paypal fa-4x"></i>
        <i class="fa-brands fa-cc-diners-club fa-4x"></i>
        <i class="fa-brands fa-cc-discover fa-4x"></i>
      </div>
    </div>
  </section>

  <footer class="bg-dark text-white py-5">
    <div class="container py-5">
      <div class="row justify-content-evenly justify-content-md-between">
        <div class="col-10 col-sm-10 col-md-6 mb-5 mb-md-0">
          <h5 class="mb-5 fs-1">Contacto y Ubicación</h5>
          <p><strong>Alfredo Linguini</strong></p>
          <p><i class="fa-solid fa-phone"></i> +56911111111</p>
          <p><i class="fa-solid fa-envelope"></i> alfredo.linguini@restaurantcito.cl</p>
          <p><i class="fa-solid fa-location-dot"></i> Calle Falsa 123</p>
        </div>
        <div class="col-10 col-sm-10 col-md-6 mb-5 mb-md-0">
          <h5 class="mb-5 fs-1">Desarrollado por Curso 0044</h5>
          <div class="d-flex justify-content-evenly">
            <p><i class="fa-brands fa-square-github fa-3x"></i></p>
            <p><i class="fa-brands fa-linkedin fa-3x"></i></p>
            <p><i class="fa-solid fa-envelope fa-3x"></i></p>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
