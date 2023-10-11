<template>
    <div class="not-found">
      <h1>Not Found</h1>
      <p>Oops page not found</p>
      <router-link to="/about">Go to Home</router-link>
    </div>
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue';
  
  export default defineComponent({
    name: 'NotFound',
  });
  </script>
  
  <style scoped>
  .not-found {
    text-align: center;
    padding: 20px;
  }
  </style>
  