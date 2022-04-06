<template>
  <div>
      <div class="bg-black">
        <!-- start of nav -->
        <Nav/>
        <!-- end of nav -->
        <!-- Landing start -->
        <LandingPage></LandingPage>
        <!-- Landing end -->
        <!-- Marquee Tag shuru -->
        <Marquee/>
        <!-- Marquee Tag khatam-->
        <!-- startt of bhangggg -->
        <CriticalGrid/>
        <!-- end of bhanggg-->
        <!-- start of whats on the wall -->
        <Wall/>
        <!-- end of woaahall -->
        <!-- start of clay collectibles -->
        <Clay/>
        <!-- end of clay collectibles -->
        <!-- Start of contact div -->
        <Contact/>        
        <!-- end of contact -->
      </div>
  </div>
</template>

<script>
import LandingPage from '../components/Sections/LandingPage.vue'
import Marquee from '../components/Sections/Marquee.vue'
import CriticalGrid from '../components/Sections/CriticalGrid.vue'
import Wall from '../components/Sections/Wall.vue'
import Clay from '../components/Sections/Clay.vue'
import Contact from '../components/Sections/Contact.vue'
import Nav from '../components/Sections/Nav.vue';
export default {
  components:{
    LandingPage,
    Marquee,
    CriticalGrid,
    Wall,
    Clay,
    Contact,
    Nav
  }
};
</script>

<style>
</style>