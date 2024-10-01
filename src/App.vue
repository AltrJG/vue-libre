<template>
  <div id="app">
    <header>
      <img src="@/assets/icon.svg" alt="Icon" class="logo" />
      <h1 class="title">Bienvenido a Navío Naranja</h1>
    </header>
    <HeroSection />
    <footer>
      <p>&copy; 2024 Tienda de Discos - Todos los derechos reservados</p>
    </footer>
  </div>
</template>

<script>
import HeroSection from './components/HeroSection.vue';

export default {
  name: 'App',
  components: {
    HeroSection
  }
};
</script>

<style>
#app {
  text-align: center;
}

header {
  background-color: #333;
  padding: 20px;
  color: white;
}

.logo {
  height: 100px;
}

.title {
  font-size: 2.5em;
  margin: 10px 0;
}

footer {
  background-color: #333;
  color: white;
  padding: 10px;
  position: absolute;
  bottom: 0;
  width: 100%;
}
</style>
