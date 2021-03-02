<template>
  <div class="home">
    <div class="content">
      <img src="https://www.touchbyme.net/assets/img/team/main-logo.jpg"
        alt=""
        class="img-fluid"
        style="max-height: 750px; width: 100%;"
      />
    </div>
    <br /><br />
    <br /><br />
    <br /><br />
    <img alt="MDB logo" src="../assets/main.png">
    <HelloWorld msg="Welcome to Your Leading Decorator"/>
    <div class="container">
      <!-- Carousel wrapper -->
      <div
      id="carouselBasicExample"
      class="carousel slide carousel-fade"
      data-mdb-ride="carousel"
      >
      <!-- Indicators -->
      <div class="carousel-indicators">
        <button
          type="button"
          data-mdb-target="#carouselBasicExample"
          data-mdb-slide-to="0"
          class="active"
          aria-current="true"
          aria-label="Slide 1"
        ></button>
        <button
          type="button"
          data-mdb-target="#carouselBasicExample"
          data-mdb-slide-to="1"
          aria-label="Slide 2"
        ></button>
        <button
          type="button"
          data-mdb-target="#carouselBasicExample"
          data-mdb-slide-to="2"
          aria-label="Slide 3"
        ></button>
      </div>

      <!-- Inner -->
      <div class="carousel-inner">
        <!-- Single item -->
        <div class="carousel-item active">
          <img
            src="https://images.unsplash.com/photo-1529636695044-9e93499f4de3?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
            class="d-block w-100"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h1>Layout Beautiful Decor</h1>
            <h5>Wedding of Mr. & MRs. Jones - North Carolina - 2017.</h5>
          </div>
        </div>

        <!-- Single item -->
        <div class="carousel-item">
          <img
            src="https://images.unsplash.com/photo-1505944357431-27579db47558?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1352&q=80"
            class="d-block w-100"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h1>Everyone Is Invited</h1>
            <h5>Seating the family and keeping the expectation.</h5>
          </div>
        </div>

        <!-- Single item -->
        <div class="carousel-item">
          <img
            src="https://images.unsplash.com/photo-1505403858922-407e2bfdf959?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
            class="d-block w-100"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h1>Gender Reveal</h1>
            <h5>For those special revealing moments that come only once.</h5>
          </div>
        </div>
      </div>
      <!-- Inner -->

      <!-- Controls -->
      <button
        class="carousel-control-prev"
        type="button"
        data-mdb-target="#carouselBasicExample"
        data-mdb-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-mdb-target="#carouselBasicExample"
        data-mdb-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
      </div>
      <!-- Carousel wrapper -->
    </div>
    <br /><br /><br /><br /><br /><br />
    <div class="container">
      <div class="row">
        <div class="col-md-8">
          <div class="block1"></div>
        </div>
        <div class="col-md-4">
          <h1>Arrangements</h1>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. 
          Quod repellat nobis asperiores sint? Minima natus nemo 
          possimus ipsa amet neque voluptatem saepe 
          tenetur voluptates quis mollitia placeat quo, perferendis quidem?
          <br />
          <br />
          <a href="#" class="btn max btn-primary">Inquire</a>
        </div>
      </div>
      <br /><br />
      <br /><br />
      <br /><br />
      <div class="row">
        <h1 class="display-4">Birthday Set-Up</h1>
        <br /><br />
        <div class="col-md-12">
          <iframe width="100%" height="550" src="https://www.youtube.com/embed/awX--1q_GaA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
      </div>
      <br /><br />
      <br /><br />
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <h1>Arrangements</h1>
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. 
            Quod repellat nobis asperiores sint? Minima natus nemo 
            possimus ipsa amet neque voluptatem saepe 
            tenetur voluptates quis mollitia placeat quo, perferendis quidem?
            <br />
            <br />
            <a href="#" class="btn max btn-primary">Inquire</a>
          </div>
          <div class="col-md-8">
            <div class="block2"></div>
          </div>
        </div>
        <br /><br />
        <br /><br />
        <br /><br />
      </div>
      <div class="row">
        <h1 class="display-4">Gender Reveal</h1>
        <br /><br />
        <div class="col-md-12">
          <iframe width="100%" height="550" src="https://www.youtube.com/embed/fWH-Kff9Hdg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss" scoped>
.content {
  margin: 0;
  padding: 0;
  max-height: 750px;
}
.block1 {
  background: url(https://images.unsplash.com/photo-1529636120425-66f3708694e7?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80)
    no-repeat center center fixed; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: 450px;
  width: 100%;
}
.block2 {
  background: url(https://images.unsplash.com/photo-1516127817866-ac364f8b7197?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80)
    no-repeat center center fixed; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: 450px;
  width: 100%;
}
.max {
  border-radius: 34px;
}
</style>
