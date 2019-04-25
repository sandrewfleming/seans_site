<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link><br>
      <router-link to="/about">Resume</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #4B4C4F;
  background:#b35900;
  height:auto;
}
#nav {
  padding: 30px;
  float:left;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #7f8181;
    }
  }
}
</style>
