<template>
  <div>
    <!-- Hero Section Begin -->
    <section class="hero-section">
      <carousel class="hero-items" :items="1" :nav="false" :autoplay="true">
        <div
          class="single-hero-items set-bg"
          style="background-image: url('/img/hero-1.jpg')"
        >
          <div class="container">
            <div class="row">
              <div class="col-lg-5">
                <span>Belanja Bulanan</span>
                <h1>E-Commerce Pertama di Kota Karawang</h1>
                <p>
                  Mengantar Kebutuhan Dapur ke Rumah Anda
                </p>
                <a href="#" class="primary-btn">Shop Now</a>
              </div>
            </div>
          </div>
        </div>
        <div
          class="single-hero-items set-bg"
          style="background-image: url('/img/hero-2.jpg')"
        >
          <div class="container">
            <div class="row">
              <div class="col-lg-5">
                <span>Belanja Bulanan</span>
                <h1>Diskon terbaik Menanti Anda</h1>
                <p>
                  Menyediakan Produk dengan Harga Terjangkau
                </p>
                <a href="#" class="primary-btn">Shop Now</a>
              </div>
            </div>
          </div>
        </div>
        <div
          class="single-hero-items set-bg"
          style="background-image: url('/img/hero-3.jpg')"
        >
          <div class="container">
            <div class="row">
              <div class="col-lg-5">
                <span>Belanja Bulanan</span>
                <h1>Memberikan Kemudahan dalam Berbelanja</h1>
                <p>
                  Motto: Sekali Sentuh Seribu Kemudahan (Digital Smart Shopping)
                </p>
                <a href="#" class="primary-btn">Shop Now</a>
              </div>
            </div>
          </div>
        </div>
      </carousel>
    </section>
    <!-- Hero Section End -->
  </div>
</template>

<script>
import carousel from "vue-owl-carousel";

export default {
  name: "HeroBelanjabulanan",
  components: {
    carousel,
  },
};
</script>
