<script>
// Get the button
var rootElement = document.documentElement;

function scrollToTop() {
  // Scroll to top logic
  rootElement.scrollTo({
    top: 0,
    behavior: "smooth"
  });
}

</script>

<section>
  <header id="home" class="fade-in one">
    <nav class="navbar navbar-dark" aria-label="Sam Designer">
      <a class="navbar-brand" href="#home">Sam, Designer</a>
      <button class="navbar-toggler flex-end" type="button" data-bs-toggle="collapse" data-bs-target="#navbarsExample01"
        aria-controls="navbarsExample01" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarsExample01">
        <ul class="navbar-nav mx-2 mb-2">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#work">Work</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </nav>
  </header>

  <!--end navbar-->


  <main>

    <!--start about-->

    <section id="about" class="fade-in two py-5 text-center container">
      <div class="row py-lg-5">
        <div class="col-lg-6 col-md-8 mx-auto">
          <h1 class="fw-light">About <span class="text-success">me</span></h1>
          <p class="lead text-muted">Hi, I'm Sam, a designer with 2 years of work experience. I specialize in creating
            clean, modern and user-friendly designs. Let me know if you have a project in mind!</p>
          <p>
            <a href="#" class="btn btn-primary my-2">Download CV</a>
          </p>
        </div>
      </div>
    </section>

    <!--end about-->

    <!--start work-->

    <section id="work" class="fade-in three text-center">
      <h2>My Work</h2>
      <p>Here are a few of my favorite projects:</p>
      <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 g-3">
        <div class="col-lg-4 col-sm-6 mb-4">
          <div class="card h-100">
            <a href="#" data-bs-toggle="modal" data-bs-target="#exampleModal"><img class="card-img-top" src="https://via.placeholder.com/700x400" alt=""></a>
            <div class="card-body">
              <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet numquam
                aspernatur eum quasi sapiente nesciunt? Voluptatibus sit, repellat sequi itaque deserunt,
                dolores in, nesciunt, illum tempora ex quae? Nihil, dolorem!</p>
              <div class="d-flex justify-content-between align-items-center">
                <div class="btn-group">
                  <a href="/" type="button"
                  class="btn btn-sm btn-outline-secondary">Github</a>
                </div>
                <a href="/" type="button"
                class="btn btn-sm btn-outline-secondary">Live Demo</a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-sm-6 mb-4">
          <div class="card h-100">
            <a href="#" data-bs-toggle="modal" data-bs-target="#exampleModal"><img class="card-img-top" src="https://via.placeholder.com/700x400" alt=""></a>
            <div class="card-body">
              <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet numquam
                aspernatur eum quasi sapiente nesciunt? Voluptatibus sit, repellat sequi itaque deserunt,
                dolores in, nesciunt, illum tempora ex quae? Nihil, dolorem!</p>
              <div class="d-flex justify-content-between align-items-center">
                <div class="btn-group">
                  <a href="/" type="button"
                  class="btn btn-sm btn-outline-secondary">Github</a>
                </div>
                <a href="/" type="button"
                class="btn btn-sm btn-outline-secondary">Live Demo</a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-sm-6 mb-4">
          <div class="card h-100">
            <a href="#" data-bs-toggle="modal" data-bs-target="#exampleModal"><img class="card-img-top" src="https://via.placeholder.com/700x400" alt=""></a>
            <div class="card-body">
              <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet numquam
                aspernatur eum quasi sapiente nesciunt? Voluptatibus sit, repellat sequi itaque deserunt,
                dolores in, nesciunt, illum tempora ex quae? Nihil, dolorem!</p>
              <div class="d-flex justify-content-between align-items-center">
                <div class="btn-group">
                  <a href="/" type="button"
                  class="btn btn-sm btn-outline-secondary">Github</a>
                </div>
                <a href="/" type="button"
                class="btn btn-sm btn-outline-secondary">Live Demo</a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-sm-6 mb-4">
          <div class="card h-100">
            <a href="#" data-bs-toggle="modal" data-bs-target="#exampleModal"><img class="card-img-top" src="https://via.placeholder.com/700x400" alt=""></a>
            <div class="card-body">
              <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet numquam
                aspernatur eum quasi sapiente nesciunt? Voluptatibus sit, repellat sequi itaque deserunt,
                dolores in, nesciunt, illum tempora ex quae? Nihil, dolorem!</p>
              <div class="d-flex justify-content-between align-items-center">
                <div class="btn-group">
                  <a href="/" type="button"
                  class="btn btn-sm btn-outline-secondary">Github</a>
                </div>
                <a href="/" type="button"
                class="btn btn-sm btn-outline-secondary">Live Demo</a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-sm-6 mb-4">
          <div class="card h-100">
            <a href="#" data-bs-toggle="modal" data-bs-target="#exampleModal"><img class="card-img-top" src="https://via.placeholder.com/700x400" alt=""></a>
            <div class="card-body">
              <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet numquam
                aspernatur eum quasi sapiente nesciunt? Voluptatibus sit, repellat sequi itaque deserunt,
                dolores in, nesciunt, illum tempora ex quae? Nihil, dolorem!</p>
              <div class="d-flex justify-content-between align-items-center">
                <div class="btn-group">
                  <a href="/" type="button"
                  class="btn btn-sm btn-outline-secondary">Github</a>
                </div>
                <a href="/" type="button"
                class="btn btn-sm btn-outline-secondary">Live Demo</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!--end end-->
  
<!-- Modal Dialog -->
<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="exampleModalLabel">Explore My Projects</h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <div id="carouselExample" class="carousel slide">
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="https://via.placeholder.com/700x400" class="d-block w-100" alt="devpost-logo">
              <h4 class="pt-2">Lorem ipsum</h4>
              <p class="pt-2">Voluptatibus sit, repellat sequi itaque deserunt,
                dolores in, nesciunt, illum tempora ex quae? Nihil, dolorem!</p>
            </div>
            <div class="carousel-item">
              <img src="https://via.placeholder.com/700x400" class="d-block w-100" alt="devfolio-logo">
              <h4 class="pt-2">Lorem ipsum</h4>
              <p class="pt-2">Voluptatibus sit, repellat sequi itaque deserunt,
                dolores in, nesciunt, illum tempora ex quae? Nihil, dolorem!</p>
            </div>
            <div class="carousel-item">
              <img src="https://via.placeholder.com/700x400" class="d-block w-100" alt="devjane-logo">
              <h4 class="pt-2">Lorem ipsum</h4>
              <p class="pt-2">Voluptatibus sit, repellat sequi itaque deserunt,
                dolores in, nesciunt, illum tempora ex quae? Nihil, dolorem!</p>
            </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample"
            data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExample"
            data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal" aria-label="Button">Close</button>
      </div>
    </div>
  </div>
</div>
</div>
<!-- Exit Modal Dialog-->

    <!--start contact-->
    <section id="contact" class="fade-in four bg-contact d-flex align-items-center">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-xl-6 col-lg-8 pt-5">
            <div class="text-center mb-5 pb-4">
              <h3>Get in touch <span class="text-success">with me</span></h3>
              <form name="contact" method="POST" data-netlify="true">
                <div class="form-group mt-4">
                  <input type="text" name="name" class="form-control" placeholder="Name" />
                </div>
                <div class="form-group mt-4">
                  <input type="email" name="email" class="form-control" placeholder="Email" />
                </div>
                <div class="form-group mt-4">
                  <textarea name="message" class="form-control" placeholder="message"></textarea>
                </div>
                <div class="form-group mt-4">
                  <button class="btn btn-primary" type="submit">Send</button>
                </div>
              </form>

            </div>
          </div>
        </div>
      </div>
    </section><!--end contact-->

  </main>

  <!--scroll to top-->
  <div id="btn-top" class="justify-content-end d-flex mb-5 px-2">
    <button type="button" class="btn btn-primary" on:click={scrollToTop}><i class="fa fa-chevron-up"></i></button>
  </div>

  <footer class="fade-in five py-3 my-4">
    <!-- <ul class="nav justify-content-center border-bottom pb-3 mb-3">
      <li class="nav-item"><a href="#" class="nav-link px-2 text-white"><i class="fab fa-2x fa-twitter"></i></a></li>
      <li class="nav-item"><a href="#" class="nav-link px-2 text-white"><i class="fab fa-2x fa-linkedin"></i></a></li>
      <li class="nav-item"><a href="#" class="nav-link px-2 text-white"><i class="fab fa-2x fa-github"></i></a></li>
      <li class="nav-item"><a href="#" class="nav-link px-2 text-white"><i class="fab fa-2x fa-behance"></i></a></li>
      <li class="nav-item"><a href="#" class="nav-link px-2 text-white"><i class="fab fa-2x fa-dribbble"></i></a></li>
    </ul> -->
    <strong class="text-center text-white">Copyright © 2023 Sam</strong>
  </footer>
</section>

<style>

</style>
