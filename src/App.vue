<template>
  <header>
    <img src="./assets/images/logo.svg" alt="Shortly logo" />
    <NavBar />
  </header>

  <main>
    <!-- <HeroSection/>
  <UrlInput/>
  <StatisticsSection /> -->
  </main>
</template>

<script setup>
// import HeroSection from './components/HeroSection.vue'
// import UrlInput from './components/UrlInput.vue'
// import StatisticsSection from './components/StatisticsSection.vue'
import NavBar from './components/NavBar.vue'
</script>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1.5em;
  line-height: 1.5;
}
</style>
