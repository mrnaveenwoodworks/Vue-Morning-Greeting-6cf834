<template>
  <div class="min-h-screen flex flex-col items-center justify-center bg-gradient-to-b from-blue-100 to-blue-200 p-4">
    <div class="max-w-md w-full bg-white rounded-lg shadow-lg p-6">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 256 256" width="64" height="64"><rect width="256" height="256" fill="none"/><line x1="128" y1="36" x2="128" y2="32" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><circle cx="128" cy="128" r="56" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="60" y1="60" x2="56" y2="56" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="60" y1="196" x2="56" y2="200" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="196" y1="60" x2="200" y2="56" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="196" y1="196" x2="200" y2="200" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="36" y1="128" x2="32" y2="128" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="128" y1="220" x2="128" y2="224" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/><line x1="220" y1="128" x2="224" y2="128" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"/></svg>
      <h1 class="text-4xl font-bold text-center text-blue-800 mb-6">Vue Morning Greeting</h1>
      <GreetingMessage />
      <div class="mt-8 text-center text-sm text-gray-500">
        <p>Have a wonderful day!</p>
      </div>
    </div>
  </div>
</template>

<script>
import GreetingMessage from "./components/GreetingMessage.vue";

export default {
  name: "App",
  components: {
    GreetingMessage
  }
};
</script>