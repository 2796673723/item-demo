<template>
  <div id="app">
    <HelloWorld :msg="msg" :name="name" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
  props: {
    name: {
      type: String,
      default: "",
    },
    msg: {
      type: String,
      default: "",
    },
  },
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
}
#app {
  height: 100vh;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
