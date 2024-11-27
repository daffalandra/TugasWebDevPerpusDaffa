<script setup>
import { RouterView } from 'vue-router';
import Nav from './components/Nav.vue';
</script>

<template>
  <Nav></Nav>
  <div class="m-3">
    <RouterView></RouterView>
  </div>
</template>