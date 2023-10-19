<template>
    <nav class="navbar navbar-expand-lg static-top" style="background-color: rgba(0, 0, 0, 0.4);">
  <div class="container">
    <a class="navbar-brand" href="#">
      <img class="logo" src="@/assets/crown.png" alt="..." height="36">
      <b>KING</b>
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Shop</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact us</a>
        </li>
        <li class="nav-item">
          <button class="btn btn-dark" style="border-radius: 20px;"><a>Sign up</a></button>
        </li>
      </ul>
    </div>
  </div>
</nav>  
</template>


<script>
export default {
  name: 'NavBar',
}
</script>

<style scoped>
header {
  width: 100%;
}

.logo {
  margin-right: 15px;
  width: 40px;
  height: 40px;
}

.nav-item{
  font-weight: 600;
  margin-left: 3rem;
  
}

@media (max-width: 768px) {
.navbar-collapse {
    height: 100vh;
    text-align: center;
    font-size: x-large;
}
}

</style>
