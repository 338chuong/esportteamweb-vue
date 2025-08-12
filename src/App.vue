<template>
  <div>
    <MainHeader />

    <div id="heroCarousel" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="2" aria-label="Slide 3"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="3" aria-label="Slide 4"></button>
      </div>

      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="/img/slide1.png" class="d-block w-100" alt="Slide 1" />
          <div class="carousel-caption d-none d-md-block">
            <h5>Vô địch PUBG Global Championship</h5>
          </div>
        </div>
        <div class="carousel-item">
          <img src="/img/slide2.png" class="d-block w-100" alt="Slide 2" />
          <div class="carousel-caption d-none d-md-block">
            <h5>Vô địch CS2 IEM Ha Noi</h5>
          </div>
        </div>
        <div class="carousel-item">
          <img src="/img/slide3.png" class="d-block w-100" alt="Slide 3" />
          <div class="carousel-caption d-none d-md-block">
            <h5>Vô địch CKTG Liên Minh Huyền Thoại</h5>
          </div>
        </div>
        <div class="carousel-item">
          <img src="/img/slide4.png" class="d-block w-100" alt="Slide 4" />
          <div class="carousel-caption d-none d-md-block">
            <h5>Các thành viên đội tuyển DoTA2 dành được danh hiệu cao quý nhất</h5>
          </div>
        </div>
      </div>

      <button class="carousel-control-prev" type="button" data-bs-target="#heroCarousel" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#heroCarousel" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>

    <NewsSection />

    <SiteFooter />
  </div>
</template>

<script setup>
import MainHeader from './components/MainHeader.vue'
import NewsSection from './components/NewsSection.vue'
import SiteFooter from './components/SiteFooter.vue'
</script>

<style scoped>
/* Scoped styles specific to App can go here if needed */
</style>

