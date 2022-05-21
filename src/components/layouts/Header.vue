<script setup>
import { ref } from 'vue'

defineProps({
  header: String
})

const count = ref(0)
</script>

<template>
  <nav class="bg-slate-800 text-white border-gray-200 px-2 py-2">
    <div class="container flex flex-wrap justify-between items-center mx-auto">
      <a href="https://tesimune.vercel.app" class="flex items-center">
          <img src="../../assets/logo.png" class="mr-1 h-6 sm:h-9" alt="throne Logo" />
          <span class="self-center text-xs md:text-xl font-semibold whitespace-nowrap dark:text-white">Throne Of Grace Holy City</span>
      </a>
      <div class="flex justify-center items-center md:order-2">
          <div class="flex text-white">
          
          <svg xmlns="http://www.w3.org/2000/svg" data-modal-toggle="authentication-modal" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
          </svg>
          </div>
          <button data-collapse-toggle="mobile-menu-4" type="button" class="inline-flex items-center p-2 text-sm text-white rounded-lg md:hidden" aria-controls="mobile-menu-4" aria-expanded="false">
          <span class="sr-only">Open main menu</span>
          <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path></svg>
          <svg class="hidden w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
        </button>
      </div>
      <div class="hidden justify-between items-center w-full md:flex md:w-auto md:order-1" id="mobile-menu-4">
        <ul class="flex flex-col mt-4 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium">
          <li>
            <a href="#" class="block py-2 pr-4 pl-3 text-white bg-blue-700 rounded md:bg-transparent md:text-blue-700 md:p-0" aria-current="page">Home</a>
          </li>
          <li>
            <a href="#" class="block py-2 pr-4 pl-3 text-white md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0">About</a>
          </li>
          <li>
            <a href="#" class="block py-2 pr-4 pl-3 text-white md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0">Services</a>
          </li>
          <li>
            <a href="#" class="block py-2 pr-4 pl-3 text-white md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
