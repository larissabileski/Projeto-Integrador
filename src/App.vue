<script>
import { RouterView, RouterLink } from "vue-router";
export default { components: RouterView, RouterLink };
</script>

<template>
  <header>
    <div class="container">
  <div class="row row-cols-auto">
        <div class="titulo">
      <h1>Belos Destinos</h1>
    </div>
   <div class="home">
      <router-link to="/" style="color:black">Inicio</router-link>
    </div>
   <div class="sobre">
      <router-link to="/about" style="color:black">Outras opções</router-link>
    </div>
  </div>
</div>
    
  </header>
  <main><RouterView /></main>
  <footer>Entre em contato com belosdestinos@gmail.com</footer>
</template>

<style>
#app {
  height: 100vh;
}
header {
  height: 15%;
  background: #0e6b88;
  padding-bottom: 120px;
}
main {
  height: 250vh;
  background: #f2e5ca;
}
footer{
  background: #f2e5ca;
  text-align: center;
  padding-bottom: 20px;
}
.titulo {
  font-family: "Times New Roman", Times, serif;
  text-align: left;
  padding-left: 5px;
  padding-top: 30px;

}
.home {
  float: left;
  border: none;
  padding-top: 45px;
  padding-left: 70px;
  width: 200px;
  font-family: Arial, Helvetica, sans-serif white;
}

.sobre {
  float: left;
  border: none;
  padding: 0px;
  width: 200px;
  padding-top: 45px;
}
</style>
