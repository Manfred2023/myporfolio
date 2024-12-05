<template>
  <div class="bg-indigo-600   px-5 sm:px-10 lg:px-20 py-10">
    <div class="h-full w-full flex flex-col justify-between">
      <!-- Header -->
      <div class="w-full flex flex-wrap justify-between items-center space-y-5 sm:space-y-0">
        <h1 class="text-white font-bold text-lg sm:text-xl">FredCode</h1>
        <nav class="flex flex-wrap space-x-5">
          <a href="#home" class="text-white text-sm sm:text-base">Home</a>
          <a href="#about" class="text-white text-sm sm:text-base">About</a>
          <a href="#services" class="text-white text-sm sm:text-base">Services</a>
          <a href="#portfolio" class="text-white text-sm sm:text-base">Portfolio</a>
          <a href="#contact" class="text-white text-sm sm:text-base">Contact</a>
        </nav>
        
        <a href="/src/assets/cv/manfred.pdf" download="Manfred_Moukate_CV" class="bg-amber-500 text-white hover:bg-white hover:text-blue-500 font-light py-2 px-4 rounded-full transition duration-300 text-sm sm:text-base">
          Download CV
        </a>
      </div>

      <!-- Section description et photo -->
      <div class="flex flex-col lg:flex-row w-full h-full mt-5 rounded-lg overflow-hidden">
        <!-- Description -->
        <div class="w-full lg:w-1/2 flex flex-col justify-center items-center px-5 lg:px-10 text-center lg:text-left">
          <h6 class="text-white text-2xl sm:text-4xl font-bold">
            Hello, I'm Manfred MOUKATE Software engineer, expert in mobile and web development.
          </h6>
          <p class="text-white text-base sm:text-lg mt-5 font-light">
            I'm a passionate software engineer with a deep understanding of mobile and web development.
          </p>
          <div class="flex flex-col sm:flex-row space-y-3 sm:space-y-0 sm:space-x-5 mt-5">
            <button class="bg-amber-500 text-white hover:bg-white hover:text-blue-500 font-light py-2 px-4 rounded-full transition duration-300">
              Get Started
            </button>
            <button class="bg-transparent hover:bg-blue-500 hover:border-transparent text-white font-light hover:text-white py-2 px-4 border border-white rounded-full">
              Contact us
            </button>
          </div>
        </div>
        <!-- Photo -->
        <div class="w-full lg:w-1/2 flex justify-center items-center rounded-lg mt-5 lg:mt-0">
          <img src="/src/assets/image/cats.jpg" alt="photo" class="w-3/4 sm:w-2/3 lg:w-3/4" />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* Ajoutez vos styles personnalisés ici si nécessaire */
</style>
