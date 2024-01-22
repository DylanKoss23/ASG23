<template>
  <header>
    <div>
      <NuxtLink to="/">Logo: DOGES</NuxtLink>
    </div>
    <nav>
      <NuxtLink to="doge">Doge</NuxtLink>

    </nav>
  </header>
</template>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  gap: 2rem;
  padding: 2rem;
  color: white;
  background-color: black;
}
a {
  color: white;
  text-decoration: none;
}
a:hover {
  color: blue;
}
nav {
  display: flex;
  justify-content: space-between;
  gap: 12px;
}
</style>