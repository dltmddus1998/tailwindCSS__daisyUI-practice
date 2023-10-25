<template>
  <div class="drawer lg:drawer-open">
    <input id="my-drawer-2" type="checkbox" class="drawer-toggle" />
    <div class="drawer-content flex flex-col items-center justify-center">
      <!-- TODO: Table here!! -->
    </div>
    <div class="drawer-side">
      <label for="my-drawer-2" aria-label="close sidebar" class="drawer-overlay"></label>
      <ul class="menu p-4 w-80 min-h-full bg-[#7752FE] text-base-content">
        <!-- Sidebar content here -->
        <li><a class="underline hover:underline-offset-4">Profile</a></li>
        <li><a>Users</a></li>
      </ul>
    </div>
  </div>
</template>

<script setup>
require('tailwindcss/tailwind.css');
require('daisyui/dist/full.css');
</script>

<style></style>
