<template>
  <main>
    <h1>Hello World!</h1>
    <NuxtLink to='/fun'>Fun page</NuxtLink>
  </main>
</template>

<style scoped>
  h1 {
    @apply p-2 m-2 text-lg 
  }

  a {
    display: block;
    padding: 1em;
    margin: 1em;
    background-color: yellow;
    font-size: large;
  }


</style>