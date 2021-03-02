<template>
  <div class="hello">
    <h3>{{ msg }}</h3>
    <h5 class="container">
      If you need a service to decorate for an upcoming event, reach out today.
      You may also see our previous work below from previous clients.
    </h5>
    <br /><br />
    <br /><br />
    <div class="container">
      <h1 class="display-3">Reach Out To Us</h1>
      <div class="container">
        <a target="_blank" style=" background-color: #E0C521; color: white; height: 40px; text-transform: uppercase; font-family: 'Square Market', 'helvetica neue', helvetica, arial, sans-serif; letter-spacing: 1px; line-height: 38px; padding: 0 28px; border-radius: 3px; font-weight: 500; font-size: 14px; cursor: pointer; display: inline-block; " href="https://square.site/book/L454ZNV40DNRM/touched-by-me-decorating">Book an Appointment</a>
      </div>
      <div class="row">
        <div class="col-md-6">
          <img src="https://www.touchbyme.net/assets/img/team/owner.jpg"
          class="img-fluid img"
          width="100%"
          alt="" /> <br />
          <h3 class="text-center">CRYSTAL HAYMON</h3>
          <!-- Section: Social media -->
          <section class="mb-4">
            
            <!-- HeadSet -->
            <a href="#" class="round1">
              <i class="fas text-primary fa-headset"></i>
            </a>

            <!-- Facebook -->
            <a
              class="round"
              href="#!"
              >
              <img width="40px" src="../assets/fb.png" alt="" />
            </a>
      
            <!-- LinkedIn -->
            <a
              class="round"
              href="#!"
              >
              <img width="40px" src="../assets/in.png" alt="">
            </a>
  
            <!-- HeadSet -->
            <a href="#" class="round1">
              <i class="far text-primary fa-envelope"></i>
            </a>
  
          </section>
          <!-- Section: Social media -->
        </div>
        <div class="col-md-6">
          <img src="https://www.touchbyme.net/assets/img/team/alexis.jpg"
          class="img-fluid img"
          width="100%"
          alt="" /> <br />
          <h3 class="text-center">ALEXIS MOORE</h3>
          <!-- Section: Social media -->
          <section class="mb-4">
            
            <!-- HeadSet -->
            <a href="#" class="round1">
              <i class="fas text-primary fa-headset"></i>
            </a>

            <!-- Facebook -->
            <a
              class="round"
              href="#!"
              >
              <img width="40px" src="../assets/fb.png" alt="" />
            </a>
      
            <!-- LinkedIn -->
            <a
              class="round"
              href="#!"
              >
              <img width="40px" src="../assets/in.png" alt="">
            </a>
  
            <!-- HeadSet -->
            <a href="#" class="round1">
              <i class="far text-primary fa-envelope"></i>
            </a>
  
          </section>
          <!-- Section: Social media -->
        </div>
      </div>
      <br /><br />
      <br /><br />
      <!-- Grid container -->
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  font-weight: normal;
  padding-top: 20px;
  padding-bottom: 30px;
}
p {
  color: #969696;
  margin-bottom: 0;
  font-size: 14px;
}
.round {
  padding: 20px;
}
.round1 {
  padding: 20px;
  font-size: 2em;
}
.img {
  width: 270px;
  max-height: 270px;
  border-radius: 50%;
}
</style>
