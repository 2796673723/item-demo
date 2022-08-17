<template>
  <h1>{msg} : {name}</h1>
</template>

<script>
export default {
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
