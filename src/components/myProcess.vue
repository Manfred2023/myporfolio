<template>
  <div class=" px-5 sm:px-10 lg:px-20 py-10 bg-gray-100">
    <div class="w-full h-full flex flex-col items-center">
      <!-- En-tête -->
      <div class="text-center mb-10">
        <h6 class="text-indigo-600 text-lg sm:text-2xl font-bold">Process</h6>
        <h6 class="text-black mt-2 text-2xl sm:text-3xl lg:text-4xl font-bold">
          My Working Process
        </h6>
      </div>

      <!-- Étapes du processus -->
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Étape 1 -->
        <div class="bg-white shadow-md rounded-lg p-6 flex flex-col items-center">
          <h6 class="text-indigo-600 text-lg font-bold">Step 1</h6>
          <p class="text-black text-center mt-2 font-light">
            Understand the client's needs and gather all necessary information.
          </p>
        </div>

        <!-- Étape 2 -->
        <div class="bg-white shadow-md rounded-lg p-6 flex flex-col items-center">
          <h6 class="text-indigo-600 text-lg font-bold">Step 2</h6>
          <p class="text-black text-center mt-2 font-light">
            Design a custom solution and plan the project phases.
          </p>
        </div>

        <!-- Étape 3 -->
        <div class="bg-white shadow-md rounded-lg p-6 flex flex-col items-center">
          <h6 class="text-indigo-600 text-lg font-bold">Step 3</h6>
          <p class="text-black text-center mt-2 font-light">
            Develop, test, and deliver the final product with quality assurance.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
