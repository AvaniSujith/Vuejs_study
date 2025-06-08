<script setup>
import Navbar from '@/components/Navbar.vue';
import Hero from '@/components/Hero.vue';
import  HomeCards from './components/HomeCards.vue';
import JobListings from './components/JobListings.vue';
</script>

<template>
  <div>
    <Navbar />
    <!-- <Hero title="Test Title" subtitle="Test Subtitle"/> -->
     <Hero />
    <HomeCards />
    <JobListings :limit="3" :show-button="true"/>
  </div>
</template>