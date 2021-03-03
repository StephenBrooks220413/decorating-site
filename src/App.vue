<template>
  <div id="app">
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg fixed-top navbar-light text-warning bg">
      <!-- Container wrapper -->
      <div class="container-fluid">
        <!-- Navbar brand -->
        <a class="a navbar-brand" href="#">TBMD</a>

        <!-- Toggle button -->
        <button
          class="navbar-toggler"
          type="button"
          data-mdb-toggle="collapse"
          data-mdb-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <i class="fas fa-bars"></i>
        </button>

        <!-- Collapsible wrapper -->
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <!-- Left links -->
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <router-link to="/" class="a nav-link active">
                Home
              </router-link>
            </li>
            <li class="nav-item">
              <router-link to="/about" class="a nav-link active">
                About
              </router-link>
            </li>
            <li class="nav-item">
              <router-link to="/gallery" class="a nav-link active">
                Gallery
              </router-link>
            </li>
          </ul>
          <!-- Left links -->

          <!-- Search form -->
          <!-- <form class="d-flex input-group w-auto">
            Accounts
          </form> -->
        </div>
        <!-- Collapsible wrapper -->
      </div>
      <!-- Container wrapper -->
    </nav>
    <!-- Navbar -->
    <router-view/>
  </div>
</template>

<script>
import * as mdb from 'mdbvue';

export default {
  mdb
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap');

#app {
  font-family: 'Roboto', Helvetica, Arial, sans-serif;
  padding-bottom: 150px;
  text-align: center;
  color: #2c3e50;
}
.bg {
  background-color: #F8BBD0;
}
.a {
  color: rgb(148, 133, 0) !important;
  font-weight: bolder;
}
</style>
