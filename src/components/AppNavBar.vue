<script setup>
  const logoName = {logo:'Mobile App'}
  const navBar = [
    'Home', 'Features', 'Pricing', 'Blog', 'Contact Us'
  ]
</script>

<template>

      <!-- ======= Header ======= -->
  <header id="header" class="fixed-top d-flex align-items-center">
    <div class="container d-flex justify-content-between align-items-center">

      <div class="logo">
        <h1><a href="#">{{ logoName.logo }}</a></h1>
      </div>

      <nav id="navbar" class="navbar">
        <ul>
          <li><a class="active " href="#">{{ navBar[0] }}</a></li>
          <li><a href="#">{{ navBar[1] }}</a></li>
          <li><a href="#">{{ navBar[2] }}</a></li>
          <li><a href="#">{{ navBar[3] }}</a></li>
          <li><a href="#">{{ navBar[4] }}</a></li>
        </ul>
        <i class="bi bi-list mobile-nav-toggle"></i>
      </nav><!-- .navbar -->
    </div>
  </header><!-- End Header -->

</template>

<style scoped>

</style>