<!--
  Hello!
  -
  Simplefolio is a clean and responsive portfolio template for Developers!
  Created by Jacobo Martinez.
  -
  Github Repo: https://github.com/cobidev/simplefolio/
  Readme: https://github.com/cobidev/simplefolio/README.md
  -
  For business & inquires, contact me -> jacobojavier98@gmail.com
-->
<!DOCTYPE html>
<html lang="en" class="sr">
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="shortcut icon" type="image/png" href="assets/favicon.png" />

    <!-- Todo: put here your site title -->
    <title>[Rian Saputra] | Software Developer</title>
    <!-- Todo: add some coding keywords below - e.g: (javascript, yourusername, etc) -->
    <meta name="keywords" content="[username], [name], skill" />
    <!-- Todo: improve your SEO by adding a small description of you -->
    <meta name="description" content="[Your name here] | Developer" />

    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
    />
    <link rel="stylesheet" href="styles.scss" />
    <script
      defer
      src="https://unpkg.com/scrollreveal@4.0.0/dist/scrollreveal.min.js"
    ></script>

    <!-- Todo: remove the below script once you finish your portfolio -->
    <script async defer src="https://buttons.github.io/buttons.js"></script>
  </head>

  <!-- Todo: read the following HTML Todos to create your stunning portfolio website -->
  <body>
    <div id="top"></div>

    <!-- **** Hero Section **** -->
    <section id="hero" class="jumbotron">
      <div class="container">
        <h1 class="hero-title load-hidden">
          Hello World! 
          <br />
          I'm <span class="text-color-main">Rian Saputra</span>
          <br />
          I'm a <span class="text-color-main">Software Developer</span>
          <br />
          I love exploring new things.
        </h1>
        <p class="hero-cta load-hidden">
          <a rel="noreferrer" class="cta-btn cta-btn--hero" href="#about"
            >Know more</a
          >
        </p>
      </div>
    </section>
    <!-- /END Hero Section -->

    <!-- **** About Section **** -->
    <section id="about">
      <div class="container">
        <h2 class="section-title load-hidden">About me</h2>
        <div class="row about-wrapper">
          <div class="col-md-6 col-sm-12">
            <div class="about-wrapper__image load-hidden">
              <img
                alt="Profile Image"
                class="img-fluid rounded shadow-lg"
                height="auto"
                width="250px"
                src="assets/profile.jpeg"
                alt="Profile Image"
              />
            </div>
          </div>
          <div class="col-md-6 col-sm-12">
            <div class="about-wrapper__info load-hidden">
              <p class="about-wrapper__info-text">
                I'm an Indonesia based software developer and very passionate about Software Development and strive to better myself as a developer.
              </p>
              <p class="about-wrapper__info-text">
                Currently working as a Full Stack Web Developer (PHP) at PT Kawan Solusi Teknologi.
              </p>
              <p class="about-wrapper__info-text">
                My hobbies are exploring new things, playing video games, watching movie and reading book while enjoying my coffee.
              </p>
              <span class="d-flex mt-3">
                <a
                  rel="noreferrer"
                  target="_blank"
                  class="cta-btn cta-btn--resume"
                  href="assets/resume.pdf"
                >
                  View Resume
                </a>
              </span>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- /END About Section -->

    <!-- **** Projects Section **** -->
    <section id="projects">
      <div class="container">
        <div class="project-wrapper">
          <h2 class="section-title dark-blue-text">Projects</h2>

          <!-- Notice: each .row is a project -->
          <div class="row">
            <div class="col-lg-4 col-sm-12">
              <div class="project-wrapper__text load-hidden">
                <h3 class="project-wrapper__text-title">eDesa</h3>
                <div>
                  <p class="mb-4">
                    eDesa is an application that helps the needs of the village community in writing letters and purchasing digital products.
                  </p>
                </div>
                <!-- <a
                  rel="noreferrer"
                  target="_blank"
                  class="cta-btn cta-btn--hero"
                  href="#!"
                >
                  See Live
                </a>
                <a
                  rel="noreferrer"
                  target="_blank"
                  class="cta-btn text-color-main"
                  href="#!"
                >
                  Source Code
                </a> -->
              </div>
            </div>
            <div class="col-lg-8 col-sm-12">
              <div class="project-wrapper__image load-hidden">
                <a rel="noreferrer" href="#!" target="_blank">
                  <div
                    data-tilt
                    data-tilt-max="4"
                    data-tilt-glare="true"
                    data-tilt-max-glare="0.5"
                    class="thumbnail rounded js-tilt"
                  >
                    <img
                      alt="Project eDesa"
                      class="img-fluid"
                      width="250px"
                      src="assets/eDesa-Dashboard.jpeg"
                    />
                  </div>
                </a>
              </div>
            </div>
          </div>
          <!-- /END Project -->

          <!-- Notice: each .row is a project -->
          <div class="row">
            <div class="col-lg-4 col-sm-12">
              <div class="project-wrapper__text load-hidden">
                <h3 class="project-wrapper__text-title">ERP PDAM</h3>
                <div>
                  <p class="mb-4">
                    ERP PDAM is an application that helps the operational needs of the company.
                  </p>
                </div>
                <!-- <a
                  rel="noreferrer"
                  target="_blank"
                  class="cta-btn cta-btn--hero"
                  href="#!"
                >
                  See Live
                </a>
                <a
                  rel="noreferrer"
                  target="_blank"
                  class="cta-btn text-color-main"
                  href="#!"
                >
                  Source Code
                </a> -->
              </div>
            </div>
            <div class="col-lg-8 col-sm-12">
              <div class="project-wrapper__image load-hidden">
                <a rel="noreferrer" href="#!" target="_blank">
                  <div
                    data-tilt
                    data-tilt-max="4"
                    data-tilt-glare="true"
                    data-tilt-max-glare="0.5"
                    class="thumbnail rounded js-tilt"
                  >
                    <img
                      alt="Project PDAM ERP"
                      class="img-fluid"
                      width="auto"
                      src="assets/PDAM-ERP.png"
                    />
                  </div>
                </a>
              </div>
            </div>
          </div>
          <!-- /END Project -->

          <!-- Notice: each .row is a project -->
          <!-- <div class="row">
            <div class="col-lg-4 col-sm-12">
              <div class="project-wrapper__text load-hidden">
                <h3 class="project-wrapper__text-title">Project Title 2</h3>
                <div>
                  <p class="mb-4">
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                    Excepturi neque, ipsa animi maiores repellendus distinctio
                    aperiam earum dolor voluptatum consequatur blanditiis
                    inventore debitis fuga numquam voluptate ex architecto
                    itaque molestiae.
                  </p>
                </div>
                <a
                  rel="noreferrer"
                  target="_blank"
                  class="cta-btn cta-btn--hero"
                  href="#!"
                >
                  See Live
                </a>
                <a
                  rel="noreferrer"
                  target="_blank"
                  class="cta-btn text-color-main"
                  href="#!"
                >
                  Source Code
                </a>
              </div>
            </div>
            <div class="col-lg-8 col-sm-12">
              <div class="project-wrapper__image load-hidden">
                <a rel="noreferrer" href="#!" target="_blank">
                  <div
                    data-tilt
                    data-tilt-max="4"
                    data-tilt-glare="true"
                    data-tilt-max-glare="0.5"
                    class="thumbnail rounded js-tilt"
                  >
                    <img
                      alt="Project Image"
                      class="img-fluid"
                      src="assets/project.jpg"
                    />
                  </div>
                </a>
              </div>
            </div>
          </div>
          <!-- /END Project -->
        </div>
      </div>
    </section>
    <!-- /END Projects Section -->

    <!-- **** Contact Section **** -->
    <section id="contact">
      <div class="container">
        <h2 class="section-title">Contact</h2>
        <div class="contact-wrapper load-hidden">
          <p class="contact-wrapper__text">Please kindly send an email to rianrrsaputra2@gmail.com for collaboration!</p>
          <a
            rel="noreferrer"
            target="_blank"
            class="cta-btn cta-btn--resume"
            href="mailto:rianrrsaputra2@gmail.com"
            >Message me</a
          >
        </div>
      </div>
    </section>
    <!-- /END Contact Section -->

    <!-- **** Footer Section **** -->
    <footer class="footer navbar-static-bottom">
      <div class="container">
        <a rel="noreferrer" href="#top" class="back-to-top">
          <i class="fa fa-angle-up fa-2x" aria-hidden="true"></i>
        </a>
        <div class="social-links">
          <a rel="noreferrer" href="https://www.instagram.com/riannnsap/" target="_blank">
            <i class="fa fa-instagram fa-inverse"></i>
          </a>
          <a rel="noreferrer" href="https://www.linkedin.com/in/rian-saputra-a80950156/" target="_blank">
            <i class="fa fa-linkedin fa-inverse"></i>
          </a>
          <a rel="noreferrer" href="https://gitlab.com/riansap" target="_blank">
            <i class="fa fa-github fa-inverse"></i>
          </a>
        </div>

        <hr />

        <!-- Notice: if you want to give me some credit, it will be huge for me! if not, put your data on it -->
        <p class="footer__text">
          © 2022 - Rian Saputra
        </p>

        <!-- TO DO: remove this entire paragraph once you finish your portfolio -->
      </div>
    </footer>
    <!-- /END Footer Section -->

    <script defer type="module" src="index.js"></script>
  </body>
</html>
