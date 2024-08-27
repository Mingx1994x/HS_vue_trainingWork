<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <div class="container">
      <div class="row col-lg-8 col-md-10">
        <div class="d-flex align-items-center">
          <div class="d-flex flex-column align-items-center">
            <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="80" height="80" />
            <HelloWorld msg="Vue新手營" />
          </div>
          <nav class="ms-5">
            <RouterLink to="/">Home</RouterLink>| <RouterLink to="/about">About</RouterLink>|
            <RouterLink to="/Week1Hw">W1_HW</RouterLink>|
          </nav>
        </div>
      </div>
    </div>
  </header>

  <RouterView />
</template>

<style scoped></style>
