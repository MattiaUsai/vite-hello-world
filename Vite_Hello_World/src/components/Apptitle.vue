<script>
export default {
  name: "title",
  data() {
    return {
      title: "questo e il mio primo progetto con vite",
    };
  },
};
</script>

<template>
  <h1>{{ title }}</h1>
</template>
<style scoped>
h1 {
  text-transform: uppercase;
  margin-bottom: 20px;
}
</style>
