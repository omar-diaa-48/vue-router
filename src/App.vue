<template>
  <nav class="flex justify-center">
    <router-link class="mx-2" exact-active-class="text-green-500" to="/"
      >Home</router-link
    >
    |
    <router-link
      class="mx-2"
      exact-active-class="text-green-500"
      :to="{ name: 'About' }"
      >About</router-link
    >
    |
    <router-link
      class="mx-2"
      exact-active-class="text-green-500"
      :to="{ name: 'Jobs' }"
      >Jobs</router-link
    >
  </nav>
  
  <ViewWrapper>
    <router-view />
  </ViewWrapper>
</template>

<script>
</script>