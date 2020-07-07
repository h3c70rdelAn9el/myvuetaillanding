<template>
  <div class="container mx-auto px-6 py-2 flex justify-between item-center">
    <router-link to="/">
      Home
    </router-link>
    <div class="block lg:hidden">
      <button class="flex items-center px-3 py-2 border rounded text-gray-500 border-gray-800 hover:text-gray-800 hover:border-teal-500 appearance-none focus:outline-none">
        <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
          <title>Menu</title>
          <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
        </svg>
      </button>
    </div>
    <div class="hidden lg:block">
      <ul class="inline-flex">
        <li>Home</li>
        <li>About</li>
        <li>Contact</li>
      </ul>
    </div>
  </div>
</template>
