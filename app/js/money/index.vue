<template>
  <div>
    <Heador/>
    <Slider/>
    <Ada/>
    <Money/>
    <Adb/>
    <Footer/>
    <Navbar/>
  </div>
</template>

<script>
import Heador from '../public/header.vue';
import Footer from '../public/footer.vue';
import Navbar from '../public/navbar.vue';
import Slider from './mslider.vue';
import Ada from './ada.vue';
import Money from './money.vue'
import Adb from './adb.vue'

  export default {
    components:{
      Heador,
      Slider,
      Footer,
      Navbar,
      Ada,
      Money,
      Adb
    }
  }
</script>

<style lang="scss">
@import '../../css/reset.scss';
  
</style>
