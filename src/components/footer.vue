<template>
  <footer class="footer container-fluid align-bottom background">
    <div class="row">
      <div class="col-1">
      </div>
      <div class="col-2 name-font text-white text-center">
        <span>Kristina Todd</span>
      </div>
      <div class="col-9"></div>
      <div class="col-1"></div>
      <div class="col-2 plain-text text-white text-center">208.995.1719</div>
      <div class="col-6"></div>
      <div class="col-3 text-white ">
        <a href="https://www.linkedin.com/in/kristina-todd" class="btn" target="_blank"><i
            class="fab fa-linkedin"></i></a>
        <a href="https://github.com/KristinaTodd" class="btn" target="_blank"><i class="fab fa-github-square"></i></a>
      </div>
    </div>
  </footer>
</template>

<script>
  import router from "../router/index"

  export default {
    name: "Footer"
  }
</script>

<style>
  .background {
    background-color: rgb(2, 2, 59);
  }

  .plain-text {
    font-family: 'Darker Grotesque', sans-serif;
  }

  .name-font {
    font-family: 'Satisfy', cursive;
    margin-bottom: 0;
    font-size: x-large;
  }

  .btn {
    color: white;
    width: 4rem;
    padding: 0;
    margin: 0;
  }
</style>