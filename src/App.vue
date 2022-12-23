<template>
  <div class="bg-black w-full h-screen">
    <div class="flex items-center justify-center flex-col w-auto">
      <div class="flex flex-col relative">
        <div>
          <h1 class="text-white text-8xl font-bold pt-20">
            GPT-3 Writing Assistant
          </h1>
        </div>
        <div class="flex items-center justify-center">
          <h2 class="pt-6 not-italic font-normal text-2xl text-gray-400">
            insert your subtitle here kjnsdf ksdkfjn skjnfksjn ksjndfs
          </h2>
        </div>
      </div>
      <div class="pt-10 relative">
        <div>
          <div>
            <textarea
              name="promp-input"
              id=""
              cols="60"
              rows="10"
              class="rounded-2xl m-2 p-4 bg-gray-900 h-36 text-white border-blue-300 border"
              placeholder="Yes, Sir!"
            ></textarea>
          </div>
        </div>
        <div class="mt-10">
          <button
            class="bg-white absolute bottom-0 right-0 p-2 rounded-2xl hover:shadow-green-600 hover:shadow-xl shadow-green-500 shadow-lg"
            @click="handleClick"
          >
            Generate
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
const handleClick = () => {
  console.log("Hello");
};
</script>
