<template>
  <header class="header">
    <ul class="nav-items">
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/users">Users</nuxt-link>
      </li>
    </ul>
  </header>
</template>

<style scoped>
.header {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 60px;
  margin-bottom: 20px;
  background-color: #ccc;
}

.nav-items {
  display: flex;
  justify-content: space-around;
  align-items: center;
  width: 80%;
  margin: 0;
  padding: 0;
  list-style: none;
}

.nav-items a {
  color: black;
  text-decoration: none;
}

.nav-items a:hover,
.nav-items a:active {
  color: white;
}
</style>
