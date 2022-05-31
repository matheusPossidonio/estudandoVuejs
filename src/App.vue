<template>
  <div id ="app">
    <Header />
    <Home />
    <Footer />
  </div>
</template>

<script>
import './style/global.css'

import Header from './components/Header';
import Home from './pages/home'
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Home,
    Footer
}
}
</script>