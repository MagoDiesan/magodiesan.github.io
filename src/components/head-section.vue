<template>
  <header >
      <section class="view">
          <div class="full-bg-img">
              <div class="container flex-center">
                  <div class="row flex-center">
                      <div class="col-12 text-center text-md-left margins">
                          <div class="red-text text-uppercase wow fadeInDown" id="a">
                              <h1 class="h1-responsive font-weight-bold mt-sm-5">Diesan Romero</h1>
                              <br>
                              <a class="btn btn-red .z-depth-4 font-weight-bold" href="#about">About Me</a>
                          </div>
                      </div>
                  </div>
              </div>
          </div>
      </section>
  </header>
</template>

<script>
  export default {
    name: 'heads'
  }

</script>


<style>
  .full-bg-img {
    background-image: url("../assets/images/background.jpg");
  }

  #a {
    animation-duration: 3s;
    animation-delay: 0.5s;
  }

  @media (max-width: 450px) {
      .margins {
          margin-right: 1rem;
          margin-left: 1rem;
      }
  }
</style>
