<template>
  <body>
  <NavBar></NavBar>
  <div class="container main">
  <div class="row">
    <div class="col-md-6 main" style="padding: 5rem; margin-top: 5rem;">
      <div style="text-align: left;">
        <h1 style="color: white;"><b>Exquisite Watches</b></h1>
        <h2 style="color: white;"><b>Choose Luxury, <span style="color: #947F6C;">Choose Us</span></b></h2>
        <p style="margin-top: 3rem; margin-bottom: 3rem; font-size: larger;">
          Discover the Perfect Watch for Every Occasion and Elevate Your Style with Timeless Elegance and Precision Craftsmanship - watch</p>
        <h1 style="color: white;"><b>$4300.00</b></h1>
      </div>
    </div>
    <div class="col-md-6 watch" style="padding-top: 5rem;">
      <div class="d-block mx-auto" style="width: 60%;">
        <img class="img-fluid" src="@/assets/watch.png">
      </div>
    </div>
  </div>
</div>


  <FooterVue></FooterVue>
</body>
</template>

<script>
import "bootstrap/dist/css/bootstrap.min.css"
import "bootstrap"
import NavBar from "./components/NavBar.vue";
import FooterVue from "./components/FooterVue.vue"

export default {
  name: 'App',
  components: {
    NavBar,
    FooterVue
  }
}
</script>

<style>
body {
  width: 100%;
  height: 100%;
  background: #F4D4B8;
  display: flex;
  flex-direction: column;
}

@media (max-width: 768px) {
  .img-fluid {
    position: relative;
    margin-top: 0; 
  }

.main, .watch {
    margin-top: -8rem;
  }
}


</style>
