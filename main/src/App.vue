<template>
  <nav>
    <router-link to="/">Főoldal</router-link> |
    <router-link to="/about">IP</router-link>
  </nav>
  <router-view/>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ff0000;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #ff0000;

    &.router-link-exact-active {
      color: #ff0000;
    }
  }
}
</style>
