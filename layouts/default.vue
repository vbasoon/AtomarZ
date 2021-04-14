<template>
  <div class="wrapper">
    <Header />
    <main>
      <div class="container">
        <Nuxt />
      </div>
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from "../components/Header/Header";
import Footer from "../components/Footer/Footer";

export default {
  components: {
    Header,
    Footer,
  },
};
</script>

<style>
html {
}
*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: "IBM Plex Sans", sans-serif;
  letter-spacing: -0.005em;
}

.wrapper {
  max-width: 500px;
  height: auto;
  margin: 0 auto;
  background: #f5f5f7;
  outline: 1px solid black;
}
</style>
