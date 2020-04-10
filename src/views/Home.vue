<template>
  <div class="home container-fluid">
    <div class="row p-2 bg-img">
      <div class="col-12 text-center"><img src="../assets/Kristina Todd.png" class="headshot"></div>

    </div>
  </div>
</template>

<script>


  export default {
    name: 'Home',

  }
</script>

<style>
  .name-font {
    font-family: 'Satisfy', cursive;
    margin-bottom: 0;
    font-size: xx-large;
  }

  .plain-text {
    font-family: 'Darker Grotesque', sans-serif;
  }

  .bg-img {
    background-image: URL("../assets/laptop.jpg");
    width: 100vw;
    height: 75vh;
    background-size: cover;

  }

  .headshot {
    height: 20rem;
    width: 20rem;
  }
</style>