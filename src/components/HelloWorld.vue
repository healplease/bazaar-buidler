<template>
  <nav class="bg-gray-800">
    <div class="container mx-auto flex justify-between items-center p-4">
      <h1 class="text-white text-2xl">Vue Tailwind</h1>
      <ul class="flex">
        <li class="ml-4">
          <router-link to="/" class="text-white">Home</router-link>
        </li>
        <li class="ml-4">
          <router-link to="/about" class="text-white">About</router-link>
        </li>
      </ul>
    </div>
  </nav>
  <main class="h-screen w-1080">
    <div class="container mx-auto p-4">
      <h1 class="text-2xl">{{ msg }}</h1>
    </div>
  </main>
</template>

<script>
export default {
  data() {
    return {
      msg: 'Hello World'
    }
  }
}
</script>