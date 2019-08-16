<template>
  <div>
      <Heador/>
      <Slider/>
      <Footer/>
      <Navbar/>
  </div>
</template>

<script>
import Heador from '../public/header.vue';
import Footer from '../public/footer.vue';
import Navbar from '../public/navbar.vue';
import Slider from './mslider.vue';


  export default {
    components:{
      Heador,
      Slider,
      Footer,
      Navbar
    }
  }
</script>

<style lang="scss">
@import '../../css/reset.scss';
  
</style>
