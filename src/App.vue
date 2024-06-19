<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/shop">Shop</RouterLink>
        <RouterLink to="/about">About Us</RouterLink>
        <RouterLink to="/contact">Contact Us</RouterLink>
        <RouterLink to="/cart">Cart</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style>

</style>
