<script setup>
import HeroSection from './components/HeroSection.vue'
import Aboutme from './components/About.vue'
</script>

<template>
  <header>
    <nav class="navbar navbar-expand-sm bg-dark">
        <div class="container-fluid d-flex justify-content-end">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item mx-2">
                        <a class="nav-link" href="#hero">Home</a>
                    </li>
                    <li class="nav-item mx-2">
                        <a class="nav-link" href="#about">About me</a>
                    </li>
                    <li class="nav-item mx-2">
                        <a class="nav-link" href="#">Projects</a>
                    </li>
                    <li class="nav-item mx-2">
                        <a class="nav-link" href="#">Contact</a>
                    </li>
                </ul>
            </div>

        </div>
    </nav>
  </header>

  <main>
    <div class="hero" id="hero">
      <HeroSection />
    </div>
    <div class="about" id="about" >
      <Aboutme />
    </div>
    
    
  </main>
</template>

<style scoped>
.about {
  background-color: #000000;
}
.navbar {
    position: fixed;
    width: 100%;
}
.navbar-toggler{
    background-color: #e0e0e0;
}

.navbar-nav{
    margin: 0 auto;
}

.nav-link {
    color: #c3c3c3;
}

.nav-link:hover {
    color: #ffffff;
}
</style>
