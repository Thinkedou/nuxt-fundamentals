<template>
  <div>
  <nav>
    <NuxtLink to="/">Home</NuxtLink>
    <NuxtLink to="/movies">Movies</NuxtLink>
  </nav>
    <NuxtPage />
  </div>
</template>
<style scoped>
nav{
  display:flex;
  gap:10px;
}
</style>
