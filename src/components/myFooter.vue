import Services from '@/components/myService.vue';
<template>
  <footer class="h-[20rem] bg-gray-800 text-white px-10 py-10">
    <!-- Conteneur principal -->
    <div class="w-full h-full flex justify-between items-center flex-col lg:flex-row">
      <!-- Section de gauche -->
      <div class="flex flex-col items-center lg:items-start">
        <h6 class="  text-2xl font-bold">Come and visit us</h6>
        <p class="text-gray-300 mt-2 text-sm">
          Makepe, 5N.410 Street, Block M<br>
          Douala, Cameroon 🇨🇲<br>
          Email: fredcode@gmail.com<br>
          Phone: +237 699 888 709 / +237 672 846 994
        </p>
      </div>

      <!-- Section centrale -->
      <div class="flex flex-col items-center">
        <h6 class="text-lime-400 text-2xl font-bold">Services</h6>
        <ul class="text-gray-300 mt-2 space-y-1">

          <li><a href="#" class="hover:text-lime-400">Cloud & Infrastruture</a></li>
          <li><a href="#" class="hover:text-lime-400">Consulting & Advisory</a></li>
          <li><a href="#" class="hover:text-lime-400">Software engineering</a></li>
          <li><a href="#" class="hover:text-lime-400">Digital technology</a></li>
          <li><a href="#" class="hover:text-lime-400">UI/UX design</a></li>
        </ul>
      </div>

      <!-- Section de droite -->
      <div class="flex flex-col items-center lg:items-end">
        <h6 class="text-lime-400 text-2xl font-bold">Follow Us</h6>
        <div class="flex space-x-4 mt-2">
          <a href="#" class="hover:text-lime-400">Facebook</a>
          <a href="#" class="hover:text-lime-400">Twitter</a>
          <a href="#" class="hover:text-lime-400">Instagram</a>
        </div>
      </div>
    </div>
    <!-- Bas de page -->
    <div class="text-center text-gray-400 mt-10 text-sm">
      2024 FredCode, All rights reserved. Privacy policy
    </div>
  </footer>
</template>
