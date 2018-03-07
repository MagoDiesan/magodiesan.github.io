<template>
  <section id="about">
  <div class="view">
    <div class="container mt-5 mb-5 a">
      <div class="row">
        <div class="col-5">
          <div class="card wow fadeInDown" id="a">
            <div class="view overlay">
              <img src="../assets/images/yo.jpg" class="img-fluid" alt="">
              <a href="#">
                <div class="mask rgba-white-slight"></div>
              </a>
            </div>
            <div class="card-body">
              <h4 class="card-title red-text">Diesan Romero</h4>
              <div class="card-text">Frontend Architect with Javascript Technology, future Systems Engineer and full-time <a href="https://platzi.com/@magodiesan/" class="red-text"> Platzi </a> student. I like magic, Artificial Intelligence, and the movies of the American Cinema.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-6 ml-5 ">
          <div class="w-100 wow fadeInRight" id="a">
            <h3 class="mt-5 red-text font-weight-bold">JavaScript</h3>
            <div class="progress">
              <div class="progress-bar progress-bar-striped bg-danger js" role="progressbar" aria-valuenow="70" aria-valuemin="0" aria-valuemax="100"></div>
            </div>
            <h3 class="mt-5 red-text font-weight-bold">NodeJS</h3>
            <div class="progress">
              <div class="progress-bar progress-bar-striped bg-danger node" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
            </div>
            <h3 class="mt-5 red-text font-weight-bold">Ruby</h3>
            <div class="progress">
              <div class="progress-bar progress-bar-striped bg-danger rb" role="progressbar" aria-valuenow="20" aria-valuemin="0" aria-valuemax="100"></div>
            </div>
            <h3 class="mt-5 red-text font-weight-bold ">Python</h3>
            <div class="progress">
              <div class="progress-bar progress-bar-striped bg-danger py" role="progressbar" aria-valuenow="10" aria-valuemin="0" aria-valuemax="100"></div>
            </div>
            <h3 class="mt-5 red-text font-weight-bold">Contact me</h3>
            <div class="social mb-5 mt-4">
              <botones></botones>
            </div>
            <!-- <div class="blog">
              <a href="#" class="btn btn-lg btn-outline-red">Go to Blog</a>
              <a href="#" class="btn btn-lg btn-outline-red">More about me</a>
            </div> -->
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
</template>

<script>
import botones from "./social.vue"
  export default {
    name: "mains",
    components: {
      botones
    }
  }
</script>

<style>

  .js {
    width: 70%;
  }
  .node {
    width: 25%;
  }

  .rb {
    width: 20%;
  }
  .py {
    width: 10%;
  }

  #a {
    animation-duration: 3s;
    animation-delay: 0.5s;
  }

  @media (max-width: 450px) {
      .col-5 {
        max-width: none;
        flex:none;
      }
      .col-6 {
        max-width: 80%;
        flex: auto;
        margin-left: 2%;
      }
      .ml-5 {
        margin-left: 1.5rem !important;
      }

      div.blog {
        display: none;
      }

      .flex-center {
        height: 100%;
      }

      .full-bg-img {
        height: 20%;
      }

      .full-height {
        height: 63.7%;
      }


  }

</style>
