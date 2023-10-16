<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from '@/components/Navbar.vue'
import Footer from '@/components/Footer.vue'


</script>

<template>
  
  <header>
   <Navbar />
  </header>

    <RouterView />

  <bottom>
    <Footer />
  </bottom>
  
</template>

<style >
@media (min-width: 992px) {
  .rounded-lg-3 { border-radius: .3rem; }
}
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: "Raleway", sans-serif;
  font-weight: 400;
}
.app{
  min-height: 100vh;
  position: relative;
  background-color: #f1f1f1;
}
.contaner{
  padding: 0 20px;
  max-width: 1140px;
  margin: 0 auto;
}


</style>
