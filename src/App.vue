<template>
  <div id="app">
    <router-view />
    <Footer />
  </div>
</template>

<script>
  import Footer from "./components/footer"
  export default {

    name: "App",
    components: {
      Footer
    }

  }
</script>

<style>

</style>