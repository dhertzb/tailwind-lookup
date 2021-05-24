<template>
  <main>
    <Navbar />
    <LandingPage />
  </main>
</template>

<script>
import Navbar from "./components/Navbar";
import LandingPage from "./components/LandingPage.vue";

export default {
  components: {
    Navbar,
    LandingPage,
  },
};
</script>
