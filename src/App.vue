<template>
<div id="app">
  <div class="flex flex-row">
    <h1 class="text-purple-500 font-bold my-8 mx-4">Paul Adeoye</h1>
    <div id="nav" class="bg-black p-4 flex flex-row">
      <router-link to="/"
        class="text-white px-4 py-2 m-1 rounded"
        exact-active-class="bg-purple-700"
        >Home</router-link>
        <router-link to="/about"
        class="text-white px-4 py-2 m-1 rounded"
        exact-active-class="bg-purple-700"
        >About</router-link>
        <router-link to="/projects"
        class="text-white px-4 py-2 m-1 rounded"
        exact-active-class="bg-purple-700"
        >Projects</router-link>
        <router-link to="/contact"
        class="text-white px-4 py-2 m-1 rounded"
        exact-active-class="bg-purple-700"
        >Contact</router-link>
    </div>
  </div>
    <router-view/>
  
</div>
</template>

<style>


#app {
  font-family: cursive, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  background: black;
  min-height: 100vh;
  width: 100%;
  margin-left: auto;
  margin-right: auto;
  margin-top: 10px;
  color: white;
}

#nav {
  padding: 30px;
  display: flex;
  align-items: flex-end;
  justify-content: flex-end;
  justify-items: flex-end;
  margin-left: 48em;
}

#nav a{
  font-weight: bold;
  color: white;
}
#nav h1 {
  display: flex;
  align-items: flex-start;
  justify-content: flex-start;
  justify-items: flex-start;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
