<template>
  <div class="app">
    <nav>
      <RouterLink to="/">Home</RouterLink> | 
      <RouterLink to="/about">About</RouterLink>
    </nav>
    <br>
    <RouterView />
  </div>
</template>
<style>
.app {
  text-align: center;
}
</style>
