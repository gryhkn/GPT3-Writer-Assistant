<script setup></script>

<template>
  <div class="bg-black h-screen">
    <div class="container mx-auto px-4 py-10">
      <h1 class="text-center text-6xl font-bold text-white mt-10">
        GPT-3 Writing Assistant
      </h1>
      <p class="text-center text-lg text-white mt-4">Write your command here</p>
      <div class="relative mx-auto w-4/5">
        <textarea
          class="h-32 px-4 py-4 rounded-lg shadow-lg bg-white text-gray-800 font-medium"
          rows="10"
        ></textarea>
        <button
          class="absolute bottom-0 right-0 bg-orange-500 px-4 py-2 rounded-full mt-4 text-white font-medium shadow-lg hover:bg-orange-600"
        >
          Generate
        </button>
      </div>
    </div>
  </div>
</template>
