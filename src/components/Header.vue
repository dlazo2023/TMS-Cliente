<template>
  <header>
    <div class="row">
      <div class="col-md-4 pe-0">
        <div
          style="background-color: #00235a; border-bottom-right-radius: 151px"
        >
          <img src="/public/Rectangle 2.png" alt="" class="fondologo" />
          <img src="/src/assets/logo.png" alt="" class="logo" />
          <div
            class="yellow img-fluid d-flex align-items-center text-white text-center justify-content-center"
          >
            <i class="fas fa-phone-alt" style="font-size: 24px"></i>
            <span>+18882079275</span>
          </div>
        </div>
      </div>
      <div class="col-md-8 px-0">
        <div class="row" style="background-color: #00235a">
          <div class="col-md-12">
            <div class="top row py-3">
              <div class="col-md-4">
                <span class="adresstime">
                  <i class="fas fa-map fa-1x me-2 text-warning"></i>
                  2500 Southbranch Blvd A, United States</span
                >
              </div>
              <div class="col-md-4">
                <span class="adresstime">
                  <i class="fas fa-clock fa-1x me-2 text-warning"></i> Mon -
                  Sat: 8 am - 5 pm, Sunday: CLOSED</span
                >
              </div>

              <div class="col-md-4 d-flex justify-content-center text-center">
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
            <nav class="navbar navbar-expand-lg navbar-dark py-2 px-0">
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
  .yellow {
    background-image: url("/public/Rectangle\ 4.png");
    height: 42px;
    background-repeat: no-repeat;
    position: absolute;
    left: 0;
    top: 6rem;
    width: 402px;
    background-size: contain;
  }
  .logo {
    position: absolute;
    left: calc(100% - 78%);
    max-height: 120px;
  }
  .fondologo {
    width: 100%;
    height: 146px;
  }
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
