<template>
    <div class="about">
      <h1>Welcome to the About Page</h1>
      <p>This is the about page</p>
      <router-link to="/about">Go to Home</router-link>
    </div>
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue';
  
  export default defineComponent({
    name: 'About',
  });
  </script>
  
  <style scoped>
  .about {
    text-align: center;
    padding: 20px;
  }
  </style>
  