<template>
  <nav class="flex justify-center">
    <router-link exact-active-class="text-green-500" to="/">Home</router-link> |
    <router-link exact-active-class="text-green-500" :to="{name:'About'}">About</router-link>
  </nav>
  <router-view />
</template>