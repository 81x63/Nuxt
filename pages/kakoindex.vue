<template>


    <nav class="navbar navbar-expand-lg navbar-light bg-dark py-3 sticky-top">
      <div class="container">
        <a class="navbar-brand" href="#">
          <h2 class="pt-2 text-white">過去</h2>
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
              <a class="nav-link" href="#features">Past</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#music">Music</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">Contact</a>
            </li>
          </ul>
          <a href="https://tak-hz-solid-succotash-xg7q69jjvqwfpp76-3000.preview.app.github.dev/" class="btn btn-primary ms-3">現在</a>
        </div>
      </div>
    </nav>
    <!-- Hero section -->
    <div class="hero vh-50 d-flex align-items-center" id="home">
      <div class="container">
        <div class="row">
          <div class="col-lg-7 mx-auto text-center">
            <h1 class="display-4 text-white">過去</h1>
            <p class="text-white my-3">
              <br>
            </p>
            <nuxt-link to="/about"></nuxt-link>
            <a href="https://tak-hz-solid-succotash-xg7q69jjvqwfpp76-3000.preview.app.github.dev/miraiindex" class="btn btn-outline-primary">未来</a>
          </div>
        </div>
      </div>
    </div>
      <div class="container">
                  <h6 class="text-primary">PAST</h6>
                  <h1>過去から現在まで</h1>
                  <p>
                  </p>
                    <div class="feature d-flex mt-5"></div>
                    <div>
                      <h5>2003年</h5>
                      <p>
                        富山県で産まれる
                      </p>
                    </div>
                  <div class="feature d-flex mt-5"></div>
                    <div>
                      <h5>2009年</h5>
                      <p>
                        滋賀県に引っ越す
                      </p>
                  </div>
                  <div class="feature d-flex mt-5"></div>
                    <div>
                      <h5>2014年</h5>
                      <p>
                        小5年ダンスを習いだす
                      </p>
                  </div>
                  <div class="feature d-flex mt-5"></div>
                    <div>
                      <h5>2022年</h5>
                      <p>
                        京都TEC入学
                      </p>
                  </div>
                  </div>
<!-- Project section -->
    <section id="music">
      <div class="container-fluid">
        <div class="row mb-4">
          <div class="col-md-8 mx-auto text-center">
            <h6 class="text-primary">music</h6>
            <h1>過去をイメージして作ったplaylist</h1>
            <iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/3cSGOMcsmrxyN0fv63QlSx?utm_source=generator" width="100%" height="352" frameBorder="0" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
          </div>
        </div>
      </div>
    </section>

    <!-- contact -->
    <section id="contact" class="bg-light">
      <div class="container">
        <div class="row mb-4 ">
          <div class="col-md-8 mx-auto text-center">
            <h6 class="text-primary">Contact</h6>
            <h1>お問い合わせ</h1>
          </div>
        </div>

        <form action="" class="row g-3 justify-content-center">
          <div class="col-md-5">
            <input type="text" class="form-control" placeholder="氏名">
          </div>
          <div class="col-md-5">
            <input type="text" class="form-control" placeholder="メールアドレス">
          </div>
          <div class="col-md-10">
            <input type="text" class="form-control" placeholder="件名">
          </div>
          <div class="col-md-10">
            <textarea name="" id="" cols="30" rows="5" class="form-control" placeholder="内容"></textarea>
          </div>
          <div class="col-md-10 d-grid">
            <button class="btn btn-primary"></button>
          </div>
        </form>
      </div>
    </section>

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
              <li><a href="#features">Features</a></li>
              <li><a href="#photograph">Music</a></li>
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
</template>
