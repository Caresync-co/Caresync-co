<template>
  <div id="app">
    <header>
      <!-- Header component -->
      <Header />
    </header>
    <main>
      <!-- Router view for rendering different pages -->
      <router-view />
    </main>
    <footer>
      <!-- Footer component -->
      <Footer />
    </footer>
  </div>
</template>

<script>
// Import necessary components
import Header from './components/layout/Header.vue';
import Footer from './components/layout/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Footer
  }
};
</script>

<style>
/* Global styles for the app */
</style>
