<script setup>
import { ref } from 'vue'
import Header from './components/layouts/Header.vue'
import Slider from './components/layouts/Slider.vue'
import Index from './components/Index.vue'
import Footer from './components/layouts/Footer.vue'
</script>

<template>

    <main class="bg-black" id="app">

        <Header />
        <Slider />

        <Index></Index>

        <Footer />

    </main>
  
</template>