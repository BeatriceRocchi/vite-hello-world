<script>
export default {
  data() {
    return {
      title: "Vite Hello World",
      text: 'Vite (French word for "quick", pronounced /vit/, like "veet") is a build tool that aims to provide a faster and leaner development experience for modern web projects.',
      logoUrl: "https://vitejs.dev/logo-with-shadow.png",
    };
  },
};
</script>

<template>
  <div class="box-container">
    <img :src="logoUrl" alt="Logo Vite" />
    <h1>{{ title }}</h1>
    <p>{{ text }}</p>
  </div>
</template>

<style scoped>
.box-container {
  padding: 0 300px;
  text-align: center;
}

img {
  height: 350px;
}

h1 {
  font-size: 4rem;
  margin-bottom: 20px;
  text-shadow: 0 0 40px rgb(189, 52, 254);
}

h1:hover {
  color: rgb(255, 220, 52);
}

p {
  font-size: 2rem;
}
</style>
