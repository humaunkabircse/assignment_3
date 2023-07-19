<script setup>
const signUpImg = {
  img:'/assets/img/undraw_svg_1.svg',
  alt: 'signUpImg',
  class:'img-fluid'
}

const signUpStep = [
  {
    serial: '01',
    title: 'Sign Up',
    description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem, optio.'
  },
  {
    serial: '02',
    title: 'Create Profile',
    description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem, optio.'
  },
  {
    serial: '03',
    title: 'Enjoy the app',
    description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem, optio.'
  }
]
</script>

<template>
<section class="section">
  <div class="container">
    <div class="row justify-content-center text-center mb-5" data-aos="fade">
      <div class="col-md-6 mb-5">
        <img :src="signUpImg.img" :alt="signUpImg.alt" :class="signUpImg.class">
      </div>
    </div>

    <div class="row">
      <div class="col-md-4">
        <div class="step">
          <span class="number">{{ signUpStep[0].serial }}</span>
          <h3>{{ signUpStep[0].title }}</h3>
          <p>{{ signUpStep[0].description }}</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="step">
          <span class="number">{{ signUpStep[1].serial }}</span>
          <h3>{{ signUpStep[1].title }}</h3>
          <p>{{ signUpStep[1].description }}</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="step">
          <span class="number">{{ signUpStep[2].serial }}</span>
          <h3>{{ signUpStep[2].title }}</h3>
          <p>{{ signUpStep[2].description }}</p>
        </div>
      </div>
    </div>
  </div>
</section>
</template>

<style scoped>
</style>