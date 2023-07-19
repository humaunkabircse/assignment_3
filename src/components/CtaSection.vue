<script setup>
const publish = {
  title: 'Starts Publishing Your Apps',
  appleStore: 'App store', 
  iosStore: 'Google play', 
}
</script>

<template>
    <!-- ======= CTA Section ======= -->
<section class="section cta-section">
  <div class="container">
    <div class="row align-items-center">
      <div class="col-md-6 me-auto text-center text-md-start mb-5 mb-md-0">
        <h2>{{ publish.title }}</h2>
      </div>
      <div class="col-md-5 text-center text-md-end">
        <p>
          <a href="#" class="btn d-inline-flex align-items-center"><i class="bx bxl-apple"></i><span>{{ publish.appleStore }}</span></a> <a href="#" class="btn d-inline-flex align-items-center"><i class="bx bxl-play-store"></i><span>{{ publish.iosStore }}</span></a>
        </p>
      </div>
    </div>
  </div>
</section><!-- End CTA Section -->
</template>

<style>
</style>