<template>
  <div id="app">
    <div id="nav">
      <img class ="logo" alt="logo" src="./assets/AltLogoTest.png">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/contactUs">Contact Us</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="less">
body{
  background-color: #788797;
}

#app {
  background-color: #4c5f72;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.logo{
  margin-right: 60%;
}

#nav {
  padding: 30px;
  background-color: #6a7c8f;
  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: goldenrod;
    }
  }
}
</style>
