<template>
  <navbar :logo="logo_src" :alt="app_name" />
  <router-view/>
  <rodape />

</template>

<script>
import navbar from "./components/navbar.vue"
import rodape from "./components/rodape.vue"


export default {
  components: {
    navbar,
    rodape
  },
  data() {
    return {
      logo_src: "/img/logo.png",
      app_name: "MAKE YOUR BURGER"
    }
  }
}

</script>

<style>

  * {
    font-family:Helvetica;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  } 
  
  .main_container {
    margin: 50px;
    min-height: 250px;
  }

  h1 {
    text-align: center;
    font-size: 42px;
    margin-bottom: 30px;
    color: #222;
  }

</style>
