<template>
  <header>
    <div class="row">
      <div class="col-md-4"></div>
      <div class="col-md-8">
        <div class="row" style="background-color: #00235a">
          <div class="col-md-12">
            <div class="top row py-3">
              <div class="col-md-3">
                <span class="adresstime">
                  <i class="fa-brands fa-facebook-f"></i>
                  2500 Southbranch Blvd A, United States</span
                >
              </div>
              <div class="col-md-3">
                <span class="adresstime">
                  Mon - Sat: 8 am - 5 pm, Sunday: CLOSED</span
                >
              </div>

              <div class="col-md-6 d-flex justify-content-center text-center">
                <div class="d-flex align-items-center">
                  <a href="#" class="text-white me-3"
                    ><i class="fa-brands fa-facebook-f"></i
                  ></a>
                  <a href="#" class="text-white me-3"
                    ><i class="fa-brands fa-twitter"></i
                  ></a>
                  <a href="#" class="text-white me-3"
                    ><i class="fa-brands fa-linkedin"></i
                  ></a>
                  <a href="#" class="text-white"
                    ><i class="fa-brands fa-instagram"></i
                  ></a>
                </div>
              </div>
            </div>
          </div>

          <div class="col-md-12 px-0">
            <nav class="navbar navbar-expand-lg navbar-dark py-2">
              <div class="container">
                <button
                  class="navbar-toggler"
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#navbarNav"
                  aria-controls="navbarNav"
                  aria-expanded="false"
                  aria-label="Toggle navigation"
                >
                  <span class="navbar-toggler-icon"></span>
                </button>

                <div
                  class="collapse navbar-collapse justify-content-around"
                  id="navbarNav"
                >
                  <!-- Enlaces de la navbar -->
                  <ul class="navbar-nav">
                    <li class="nav-item">
                      <a class="nav-link" href="#">Plataformas</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Soluciones</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Recursos</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Precios</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Sobre</a>
                    </li>
                  </ul>

                  <!-- Botón de "Get a Quote" -->
                  <button
                    class="btn btn-warning ms-lg-3 mt-2 mt-lg-0 quote"
                    type="button"
                  >
                    Get a Quote
                  </button>
                </div>
              </div>
            </nav>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
  export default {
    name: "Header",
  };
</script>

<style scoped>
  /* Estilos para la barra superior */
  .top-bar {
    background-color: #002f6c; /* Ajusta el color a tu gusto */
    color: #ffffff;
    font-size: 0.9rem;
  }
  .adresstime {
    font-family: "Public Sans";
    color: #fff;
    font-size: 14px;
    text-align: left;
    display: inline-block;
  }

  /* Navbar principal */
  .navbar {
    background-color: #ffffff; /* Mismo color o uno distinto */
  }
  .nav-item {
    padding: 0 10px;
  }
  /* Ajustes de color para los enlaces */
  .nav-link {
    font-size: 16px;
    line-height: 26px;
    font-weight: 500;
    font-family: "Public Sans";
    color: #080c24;
    white-space: pre-wrap;
    text-align: left;
    padding: 5px 50px;
  }
  .nav-link:hover {
    color: #080c24 !important;
  }

  .quote {
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 17px 40px;
    box-sizing: border-box;
    text-align: left;
    font-size: 18px;
    color: #fff;
    font-family: Yantramanav;
  }

  /* Iconos de redes sociales */
  .top-bar a {
    color: #ffffff;
    text-decoration: none;
  }

  /* Puedes agregar más estilos según necesites */
</style>
