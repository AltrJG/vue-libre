<template>
  <div class="hero-section">
    <div class="hero-content">
      <h2>Descubre lo mejor de la música en vinilo</h2>
      <p>Explora nuestra colección de discos clásicos y modernos.</p>
      <button @click="verCatalogo">Ver catálogo</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroSection',
  methods: {
    verCatalogo() {
      alert('Explorar catálogo pronto disponible');
    }
  }
};
</script>

<style scoped>
.hero-section {
  background-image: url('@/assets/bgcover.png');
  background-size: cover;
  background-position: center;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
}

.hero-content {
  background-color: rgba(0, 0, 0, 0.6);
  padding: 20px;
  border-radius: 8px;
  text-align: center;
}

.hero-content h2 {
  font-size: 3em;
  margin-bottom: 10px;
}

.hero-content p {
  font-size: 1.2em;
}

.hero-content button {
  background-color: #e91e63;
  border: none;
  padding: 10px 20px;
  font-size: 1.2em;
  color: white;
  cursor: pointer;
  border-radius: 5px;
  transition: background-color 0.3s;
}

.hero-content button:hover {
  background-color: #d81b60;
}
</style>
