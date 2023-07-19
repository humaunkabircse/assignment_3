<script setup>
const heading = {
  headingName: 'Review From Our Users',
  title: 'Excellent App!',
  description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius ea delectus pariatur, numquam aperiam dolore nam optio dolorem facilis itaque voluptatum recusandae deleniti minus animi, provident voluptates consectetur maiores quos.',
  image: '/assets/img/person_1.jpg',
  imageTitle: '<span class="text-black">Jean Doe</span>, &mdash; App User'

}
</script>

<template>
<!-- ======= Testimonials Section ======= -->
<section class="section border-top border-bottom">
  <div class="container">
    <div class="row justify-content-center text-center mb-5">
      <div class="col-md-4">
        <h2 class="section-heading">{{ heading.headingName }}</h2>
      </div>
    </div>
    <div class="row justify-content-center text-center">
      <div class="col-md-7">

        <div class="testimonials-slider swiper" data-aos="fade-up" data-aos-delay="100">
          <div class="swiper-wrapper">

            <div class="swiper-slide">
              <div class="review text-center">
                <p class="stars">
                  <span class="bi bi-star-fill"></span>
                  <span class="bi bi-star-fill"></span>
                  <span class="bi bi-star-fill"></span>
                  <span class="bi bi-star-fill"></span>
                  <span class="bi bi-star-fill muted"></span>
                </p>
                <h3>{{ heading.title }}</h3>
                <blockquote>
                  <p>{{ heading.description }}</p>
                </blockquote>

                <p class="review-user">
                  <img :src="heading.image" alt="Image" class="img-fluid rounded-circle mb-3">
                  <span class="d-block" v-html="heading.imageTitle">
                </span>
                </p>

              </div>
            </div><!-- End testimonial item -->

           
          </div>
        </div>
      </div>
    </div>
  </div>
</section><!-- End Testimonials Section -->
</template>

<style scoped>
</style>
