<script setup>
import { RouterLink, RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>

    <div class="wrapper">
      <nav class="navbar navbar-expand-lg bg-body-tertiary">
          <div class="container-fluid">
            <RouterLink class="navbar-brand" to="#">Navbar</RouterLink>
            <div class="collapse navbar-collapse">
              <div class="navbar-nav">
                <RouterLink class="nav-link active" aria-current="page" to="/">Home</RouterLink>
                <RouterLink class="nav-link" to="/contact">Features</RouterLink>
                <RouterLink class="nav-link" to="/about">Pricing</RouterLink>

              </div>
            </div>
          </div>
        </nav>
        

<!-- 
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/contact">Contact</RouterLink>
      </nav> -->
    </div>
  </header>

  <RouterView />
</template>

