<script>
export default {
  name: "Header",
  data() {
    return {
      title: "questo e il mio primo progetto con vite",
    };
  },
};
</script>

<template>
  <header></header>
</template>

<style scoped>
header {
  height: 50px;
  background-color: aqua;
  position: fixed;
  top: 0;
  right: 0;
  left: 0;
}
</style>
