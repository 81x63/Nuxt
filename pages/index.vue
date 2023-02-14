<template>
<nav class="navbar navbar-expand-lg navbar-light bg-dark py-3 sticky-top">
      <div class="container">
        <a class="navbar-brand" href="#">
          <h2 class="pt-2 text-white">過去と未来</h2>
        </a>
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
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link" href="#home">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">Contact</a>
            </li>
          </ul>
          <a href="index.vue" class="btn btn-primary ms-3">現在</a>
        </div>
      </div>
    </nav>
    <!-- Hero section -->
    <div class="hero vh-100 d-flex align-items-center" id="home">
      <div class="container">
        <div class="row">
          <div class="col-lg-7 mx-auto text-center">
            <h1 class="display-4 text-white">過去</h1>
            <p class="text-white my-3">
              <br>
            </p>
            <a href="kakoindex.vue" class="btn btn-outline-success">過去</a>
            <a href="miraiindex.vue" class="btn btn-outline-success">未来</a>
          </div>
        </div>
      </div>
    </div>
    <footer>
      <div class="footer-top">
        <div class="container">
          <div class="row gy-4">
            <div class="col-md-4">
              <h4 class="text-white">過去と未来</h4>
            </div>
            <div class="col-md-2">
              <h5 class="text-white">Menu</h5>
              <ul class="list-unstyled">
                <li><a href="#home">Home</a></li>
                <li><a href="#contact">Contact</a></li>
              </ul>
            </div>
            <div class="col-md-4">
              <h5 class="text-white">Address</h5>
              <ul class="list-unstyled">
                <li>Address: , FL 62626</li>
                <li>Email: XXXXXX@icloud.com</li>
                <li>Phone: 000-000-000</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </footer>
</template>
