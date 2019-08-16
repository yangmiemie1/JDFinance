<template>
  <div>
    <Heador/>
    <Slider/>
    <Weifare/>
    <More/>
    <Footer/>
    <Navbar/>
  </div>
</template>

<script>
import Heador from '../public/header.vue';
import Footer from '../public/footer.vue';
import Navbar from '../public/navbar.vue';
import Slider from './islider.vue';
import Weifare from './weifare.vue';
import More from './more.vue';

  export default {
    components:{
      Heador,
      Slider,
      Footer,
      Navbar,
      Weifare,
      More
    }
  }
</script>

<style lang="scss">
@import '../../css/reset.scss';
  
</style>
