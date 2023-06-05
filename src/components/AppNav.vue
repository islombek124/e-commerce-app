<script setup lang="ts">
import AppLogo from '~/assets/AppLogo.svg'
import AppCart from '~/assets/AppCart.svg'
import AppUser from '~/assets/AppUser.png'
</script>

<template>
  <div class="block w-full">
    <nav class="flex items-center justify-between pb-4">
      <div class="flex items-center space-x-15">
        <img :src="AppLogo" alt="logo">
        <ul class="hidden items-center sm:flex space-x-7">
          <li>
            <a href="#">Collections</a>
          </li>
          <li>
            <a href="#">Men</a>
          </li>
          <li>
            <a href="#">Women</a>
          </li>
          <li>
            <a href="#">About</a>
          </li>
          <li>
            <a href="#">Contact</a>
          </li>
        </ul>
      </div>
      <div class="flex items-center space-x-12">
        <button>
          <img :src="AppCart" alt="">
        </button>
        <button class="h-11 w-11 border-2 border-transparent rounded-full hover:border-orange-600">
          <img :src="AppUser" alt="">
        </button>
      </div>
    </nav>

    <hr class="mt-3">
  </div>
</template>
