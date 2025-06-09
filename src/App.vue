<script setup>
import Navbar from '@/components/Navbar.vue';
import { RouterView } from 'vue-router';
</script>

<template>
  <div>
    <Navbar />
    <!-- <Hero title="Test Title" subtitle="Test Subtitle"/> -->
   <RouterView />
  </div>
</template>