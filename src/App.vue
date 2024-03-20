<script>
export default {
  data() {
    return {
      title: "Vite Hello World",
      text: 'Vite (French word for "quick", pronounced /vit/, like "veet") is a build tool that aims to provide a faster and leaner development experience for modern web projects.',
    };
  },
};
</script>

<template>
  <div class="box-container">
    <h1>{{ title }}</h1>
    <p>{{ text }}</p>
  </div>
</template>

<style scoped>
.box-container {
  padding: 0 300px;
  text-align: center;
}

h1 {
  font-size: 4rem;
  margin-bottom: 20px;
  text-shadow: 0 0 40px rgb(189, 52, 254);
}

p {
  font-size: 2rem;
}
</style>
