<script setup>
import Navbar from '@/components/Navbar.vue';
// import Hero from '@/components/Hero.vue';
// import HomeCards from '@/components/HomeCards.vue';
// import JobListings from '@/components/JobListings.vue';
import { RouterView } from 'vue-router';
</script>


<template>
  <Navbar />
  <!-- <Hero title="Test Title" subtitle="Test Subtitle" />
  <HomeCards />
  <JobListings :limit="3" :show-button="true" /> -->
  <RouterView />
</template>