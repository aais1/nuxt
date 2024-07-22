<template>
  <nav>
    <ul class="flex justify-start space-x-6 px-8 py-4 text-lg font-semibold text-white bg-green-500">
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/about">About</nuxt-link>
      </li>
    </ul>
  </nav>
  <div class="min-h-[80vh]">
    <NuxtPage/>
  </div>
  <Footer/>
</template>
