<template>
  <NavBar></NavBar>
  <div class="container">
    <div class="row">
      <div class="col-12 d-flex justify-content-center">
        <MainCarousel></MainCarousel>
      </div>
    </div>

    <div class="row text-start">
      <div class="col-6 col-md-2 border">
        Text 1
      </div>
      <div class="col-6 col-md-8 border">
        Text 2
      </div>
      <div class="col col-md-2 border">
        Text 3
      </div>
    </div>
  </div>
</template>

<script>
  import NavBar from "./components/NavBar";
  import MainCarousel from "./components/MainCarousel.vue";
  export default {
    name: 'App',
    components: {
      MainCarousel,
      NavBar
    }
  }
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
