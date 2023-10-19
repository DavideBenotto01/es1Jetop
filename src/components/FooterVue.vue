<template>

<footer class="text-center text-start" style="background-color:  rgba(0, 0, 0, 0.4);">
  <div class="container d-flex justify-content-center py-4">
      <img class="logo" src="@/assets/facebook.png">
      <img class="logo" src="@/assets/twitter.png">
      <img class="logo" src="@/assets/youtube.png">
  </div>
  <p style="color: white;">© 2023 Class Technologies Inc.</p>
</footer>

</template>
  
  <script>
  export default {
    name: 'FooterVue',
  }
  </script>
  

  <style scoped>
footer {
  position: fixed;
  bottom: 0;
  width: 100%;
}
.logo{
  margin-right: 15px;
  width: 40px;
  height: 40px;
}
  </style>
  