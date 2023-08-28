<template>
  <div class="flex bg-gray-800 max-w-full h-16">
    <h1 class="w-1/4 text-3xl text-white font-bold px-5 py-3">Restoran</h1>

    <div class="w-2/4 text-white text-xl px-4 py-4">
      <div class="flex justify-center space-x-20">
        <button type="button" class="hover:text-blue-500 active:text-bold">
          <NuxtLink to="/">Home</NuxtLink>
        </button>

        <button type="button" class="hover:text-blue-500 active:text-bold">
          <NuxtLink to="/data">Data</NuxtLink>
        </button>

        <button type="button" class="hover:text-blue-500 active:text-bold">
          <NuxtLink to="/about">About</NuxtLink>
        </button>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'HeaderPage',
  }
</script>
