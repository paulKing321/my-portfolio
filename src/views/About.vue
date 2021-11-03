<template>
  <div class="my-20 w-100 mx-20">
    <div class="flex">
      <div>
        <h1 class="text-4xl">I'm Paul Adeoye</h1>
        <p class="mt-5 text-2xl py-2">
          A Vuejs front end web developer. <br>I create bespoke websites to help people further go online.
        </p>
      </div>
      <img class="w-60 mx-40 border-4 border-purple-700 rounded-md " src="../assets/paulking.jpg">
    </div>
    <router-link to="/projects"
        class="text-white px-4 py-2 m-1 rounded"
        exact-active-class="bg-purple-700"
        >My Projects</router-link>
  </div>
</template>
