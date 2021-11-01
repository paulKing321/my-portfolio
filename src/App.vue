<template>
  <div id="nav" class="bg-red-500 p-4 shadow-lg flex flex-col lg:flex-row">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view/>
</template>

<style>
/* @font-face {
  font-family: Nisha;
  src: url("assets/Nisha Extended Nerd Font Complete.ttf");
  font-weight: normal;
}

@font-face {
  font-family: Nisha;
  src: url("assets/Nisha Bold Extended Nerd Font Complete.ttf");
  font-weight: bold;
}

@font-face {
  font-family: Nisha;
  src: url("assets/Nisha Light Extended Nerd Font Complete.ttf");
  font-weight: 100;
} */


#app {
  font-family: Nisha, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
