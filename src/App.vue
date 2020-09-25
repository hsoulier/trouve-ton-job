<template>
  <div
    id="app"
    class="antialiased font-sans text-set-black bg-set-white md:container"
  >
    <!-- <Login class="w-screen h-screen"/> -->
    <router-view></router-view>
  </div>
</template>

<script>
// import Login from "@/components/Login.vue";

export default {
  name: "App",
  // components: {
  //   Login,
  // },
};
</script>

<style src="./assets/tailwind.css"></style>
