<template>
  <footer class="footer bg-dark text-white pt-5 pb-4">
    <div class="container">
      <!-- Fila superior con direcciones/contacto -->
      <div class="row mb-4">
        <!-- Columna: Dirección de oficina -->
        <div class="col-md-4 col-lg-3 mb-4">
          <div class="d-flex align-items-start">
            <i class="fas fa-map-marker-alt fa-2x me-3 text-warning"></i>
            <div>
              <h5 class="mb-1">Office Address</h5>
              <p class="mb-0 small">
                2518 E. Biter Rd, Ohio <br />
                45236, United States
              </p>
            </div>
          </div>
        </div>

        <!-- Columna: Contacto -->
        <div class="col-md-4 col-lg-3 mb-4">
          <div class="d-flex align-items-start">
            <i class="fas fa-envelope fa-2x me-3 text-warning"></i>
            <div>
              <h5 class="mb-1">Contact Us</h5>
              <p class="mb-0 small">
                info@transproapp.com <br />
                +1 800-252-4456
              </p>
            </div>
          </div>
        </div>

        <!-- Columna: Horarios -->
        <div class="col-md-4 col-lg-3 mb-4">
          <div class="d-flex align-items-start">
            <i class="fas fa-clock fa-2x me-3 text-warning"></i>
            <div>
              <h5 class="mb-1">Working Hours</h5>
              <p class="mb-0 small">
                Weekdays: Mon-Fri 8am-2pm <br />
                Weekend: Sat-Sun 8am-2pm
              </p>
            </div>
          </div>
        </div>
      </div>

      <hr class="mb-5" style="border-color: rgba(255, 255, 255, 0.2)" />

      <!-- Fila intermedia con links y newsletter -->
      <div class="row">
        <!-- Columna: Logo y descripción -->
        <div class="col-md-4 col-lg-3 mb-4">
          <div class="mb-3">
            <!-- Ajusta la ruta de tu logo -->
            <img
              src="https://via.placeholder.com/150x40?text=Logo"
              alt="TransPro"
              style="max-height: 40px"
            />
          </div>
          <p class="small">
            Breve descripción de la empresa. Provee soluciones de logística y
            envíos de forma eficiente.
          </p>
        </div>

        <!-- Columna: Useful Links -->
        <div class="col-md-4 col-lg-2 mb-4">
          <h5 class="mb-3">Useful Links</h5>
          <ul class="list-unstyled">
            <li>
              <a href="#" class="text-white-50 text-decoration-none"
                >About Us</a
              >
            </li>
            <li>
              <a href="#" class="text-white-50 text-decoration-none"
                >Services</a
              >
            </li>
            <li>
              <a href="#" class="text-white-50 text-decoration-none"
                >Portfolio</a
              >
            </li>
            <li>
              <a href="#" class="text-white-50 text-decoration-none">Blog</a>
            </li>
            <li>
              <a href="#" class="text-white-50 text-decoration-none"
                >Contact Us</a
              >
            </li>
          </ul>
        </div>

        <!-- Columna: Our Services -->
        <div class="col-md-4 col-lg-3 mb-4">
          <h5 class="mb-3">Our Services</h5>
          <ul class="list-unstyled">
            <li>
              <a href="#" class="text-white-50 text-decoration-none"
                >Air Freight</a
              >
            </li>
            <li>
              <a href="#" class="text-white-50 text-decoration-none"
                >Ocean Freight</a
              >
            </li>
            <li>
              <a href="#" class="text-white-50 text-decoration-none"
                >Railway Freight</a
              >
            </li>
            <li>
              <a href="#" class="text-white-50 text-decoration-none"
                >Warehousing</a
              >
            </li>
            <li>
              <a href="#" class="text-white-50 text-decoration-none"
                >Distribution</a
              >
            </li>
          </ul>
        </div>

        <!-- Columna: Newsletter -->
        <div class="col-md-6 col-lg-4 mb-4">
          <h5 class="mb-3">SUBSCRIBE NOW</h5>
          <p class="small">
            Continually evolve worldwide vortals rather than process centric
            human capital. Subscribe for our latest news & articles. and send
            message.
          </p>
          <div class="input-group">
            <input
              type="email"
              class="form-control"
              placeholder="Enter email address"
            />
            <button class="btn btn-warning" type="button">Submit</button>
          </div>
        </div>
      </div>

      <hr class="my-4" style="border-color: rgba(255, 255, 255, 0.2)" />

      <!-- Fila inferior con copyright -->
      <div class="row">
        <div class="col-md-6">
          <p class="mb-0 small text-white-50">
            &copy; 2023
            <span class="text-warning">TransPro</span>. All rights reserved.
          </p>
        </div>
        <div class="col-md-6 text-md-end">
          <a href="#" class="text-white-50 text-decoration-none me-3"
            >Terms & Condition</a
          >
          <a href="#" class="text-white-50 text-decoration-none"
            >Privacy Policy</a
          >
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
  export default {
    name: "Footer",
  };
</script>

<style scoped>
  .footer {
    background-color: #080c24 !important;
  }

  .footer h5 {
    font-size: 1.1rem;
    font-weight: 600;
  }

  .footer a:hover {
    color: #ffffff;
  }
</style>
