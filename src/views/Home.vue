<template>
  <div class="home">
    <HeaderBelanjabulanan />
    <HeroBelanjabulanan />
    <Barang />
    <Insta />
    <Partner />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderBelanjabulanan from '@/components/HeaderBelanjabulanan.vue'
import HeroBelanjabulanan from '@/components/HeroBelanjabulanan.vue'
import Barang from '@/components/Barang.vue'
import Insta from '@/components/Insta.vue'
import Partner from '@/components/Partner.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'Home',
  components: {
HeaderBelanjabulanan,
HeroBelanjabulanan,
Barang, 
Insta,
Partner,
Footer
  }
}
</script>
