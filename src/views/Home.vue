<template>
    <div class="home">
      <h1>Welcome to the Home Page</h1>
      <p>This is the home page</p>
      <router-link to="/about">Go to About</router-link>
    </div>
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue';
  
  export default defineComponent({
    name: 'Home',
  });
  </script>
  
  <style scoped>
  .home {
    text-align: center;
    padding: 20px;
  }
  </style>
  