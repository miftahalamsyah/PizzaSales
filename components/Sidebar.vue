<template>
<div class="transition-all fixed top-0 bottom-0 min-h-screen duration-300 transform z-40 w-48 bg-white pt-7 pb-10 shadow-md hidden md:block">
  <div class="px-4 py-6">
    <div class="text-2xl">
      <svg width="40" height="40" viewBox="0 0 1024 1024" class="mx-auto icon" xmlns="http://www.w3.org/2000/svg"><path d="m519.232 503.498 267.977-443.1s195.515 98.991 221.339 334.724c-413.749 90.243-489.316 108.376-489.316 108.376z" fill="#EBA824"/><path d="M953.372 405.705c17.428-2.399 36.337-7.973 55.176-10.583C982.794 159.46 787.209 60.397 787.209 60.397l-30.41 47.768c48.826 37.466 167.292 122.91 196.573 297.54z" fill="#6E4921"/><path d="m426.872 568.34 209.203-354.198c-61.314-36.267-132.789-57.152-209.203-57.152-227.194 0-411.35 184.155-411.35 411.35s184.156 411.35 411.35 411.35 411.35-184.155 411.35-411.35c0-31.61-3.669-62.302-10.442-91.866L426.872 568.34z" fill="#EBA824"/><path d="M787.42 485.717c6.069 26.6 9.385 54.188 9.385 82.623 0 204.334-165.598 369.933-369.933 369.933S56.94 772.674 56.94 568.34s165.598-369.933 369.932-369.933c68.723 0 133.001 18.769 188.107 51.437l21.026-35.632c-61.315-36.266-132.79-57.151-209.203-57.151-227.195 0-411.35 184.155-411.35 411.35s184.155 411.35 411.35 411.35 411.35-184.155 411.35-411.35c0-31.61-3.67-62.303-10.443-91.866l-40.288 9.172z" fill="#6E4921"/><path d="M395.263 671.283a48.826 48.826 0 1 0 97.651 0 48.826 48.826 0 1 0-97.651 0Zm350.67-451.708a35.914 35.914 0 1 0 71.828 0 35.914 35.914 0 1 0-71.828 0Zm-110.211 363.3a19.827 19.827 0 1 0 39.654 0 19.827 19.827 0 1 0-39.654 0ZM387.008 897.279a19.05 19.05 0 1 0 38.1 0 19.05 19.05 0 1 0-38.1 0Z" fill="#4C2510"/><path d="M129.332 591.624a35.914 35.914 0 1 0 71.827 0 35.914 35.914 0 1 0-71.827 0Z" fill="#623520"/><path d="M334.654 515.704a23.848 23.848 0 1 0 47.697 0 23.848 23.848 0 1 0-47.697 0Zm144.36-202.923a13.759 13.759 0 1 0 27.518 0 13.759 13.759 0 1 0-27.518 0Zm376.142 60.679a13.759 13.759 0 1 0 27.517 0 13.759 13.759 0 1 0-27.517 0Z" fill="#FFFCF4"/><path d="M239.825 851.417a44.592 44.592 0 1 0 89.184 0 44.592 44.592 0 1 0-89.184 0Z" fill="#FDFDEC"/><path d="m211.672 534.543 53.342-6.703s-29.493-92.642-22.79-108.164c4.163-3.599 18.133-6.21 16.58 17.568-1.058 7.62 41.206 14.465 27.447-39.37-5.715-17.076-39.018-42.123-85.092-27.589-21.238 8.256-58.845 30.552-40.217 76.273 5.362 8.608 17.074 13.618 20.179-1.905 3.104-18.486 13.83-31.257 17.922-13.618s12.63 103.508 12.63 103.508zm321.107 240.53 31.116 38.243s57.787-67.877 73.097-70.205c4.798 1.482 13.618 11.077-5.644 21.45-6.42 2.892 8.749 39.088 43.887 2.257 10.513-12.7 13.829-50.73-19.756-79.589-16.723-12.488-52.284-30.974-78.813 5.716-4.092 8.325-2.329 19.897 11.29 14.817 15.874-6.562 30.974-4.375 19.332 7.338-11.783 11.712-74.509 59.973-74.509 59.973zm111.199-399.92-8.256 28.365s53.2 5.362 59.55 12.136c.918 2.893-.846 10.513-12.488 4.516-3.598-2.188-16.299 17.639 13.83 22.437 9.878.846 29.775-10.443 32.526-36.831.494-12.489-2.54-36.337-29.704-36.972-5.504.846-10.584 5.644-3.457 10.583 8.608 5.574 12.7 13.759 2.963 11.995s-54.964-16.228-54.964-16.228z" fill="#E8BC38"/><path d="M327.316 384.115s27.94-105.343 110.07-102.097c-1.553 35.067-10.302 102.097-110.07 102.097zM254.36 627.538s61.878 3.81 69.287 49.954c-19.756 3.034-58.14 5.645-69.287-49.954zm527.487-331.761s37.113 2.258 41.558 29.987c-11.853 1.764-34.855 3.386-41.558-29.987z" fill="#3D7C38"/></svg>
    </div>
    <ul class="mt-6 space-y-1 text-center">
      <li>
        <nuxt-link to="/" class="block rounded-lg px-4 py-2 text-sm font-medium text-gray-700" :class="{'bg-earthy-brown text-stone-50': isActive('/')}">
          Dashboard
        </nuxt-link>
      </li>

      <li>
        <nuxt-link to="/ukuran" class="block rounded-lg px-4 py-2 text-sm font-medium text-gray-700" :class="{'bg-earthy-brown text-stone-50': isActive('/ukuran')}">
          Ukuran
        </nuxt-link>
      </li>

      <li>
        <nuxt-link to="/tren" class="block rounded-lg px-4 py-2 text-sm font-medium text-gray-700" :class="{'bg-earthy-brown text-stone-50': isActive('/tren')}">
          Tren
        </nuxt-link>
      </li>
      
      <li>
        <nuxt-link to="/harga" class="block rounded-lg px-4 py-2 text-sm font-medium text-gray-700" :class="{'bg-earthy-brown text-stone-50': isActive('/harga')}">
          Harga
        </nuxt-link>
      </li>

      <li>
        <nuxt-link to="/pendapatan" class="block rounded-lg px-4 py-2 text-sm font-medium text-gray-700" :class="{'bg-earthy-brown text-stone-50': isActive('/pendapatan')}">
          Pendapatan
        </nuxt-link>
      </li>

      <li>
        <nuxt-link to="/vegetarian" class="block rounded-lg px-4 py-2 text-sm font-medium text-gray-700" :class="{'bg-earthy-brown text-stone-50': isActive('/vegetarian')}">
          Kategori
        </nuxt-link>
      </li>
    </ul>
  </div>

  
</div>

</template>

<script setup>
import { useRoute } from 'vue-router';

const route = useRoute();

const isActive = (path) => {
  return route.path === path;
};
</script>
