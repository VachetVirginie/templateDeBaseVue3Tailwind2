<template>
  <div>
    <!-- class to center image -->
    <img
      class="mx-auto"
      alt="Vue logo"
      src="./assets/logo.png">
    <HelloWorld msg="Titre 1" />
    <Test msg="Titre 2" />
    <p class="text-xl text-blue-500 font-bold my-4">This is a blue text</p>
    <button class="btn-green">Action</button>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Test from "./components/Test.vue";


export default {
    name: "App",
    components: {
        HelloWorld,
        Test
    },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
