<template>
  <div id="app">
    <Search />
    <Button buttonText="Give Feedback" />
  </div>
</template>

<script>
import Search from "./components/Search.vue";
import Button from "./components/Button.vue";

export default {
  name: "App",
  components: {
    Search,
    Button,
  },
};
</script>

<style>
/* Add global styles here */
body {
  font-family: Arial, sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #f0f0f0;
}
</style>
