<template>
  <div>
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
</style>
