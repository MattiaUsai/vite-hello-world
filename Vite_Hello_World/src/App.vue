<script>
import Paragrafo from "./components/Paragraf.vue";
import Titolo from "./components/Apptitle.vue";
import Header from "./components/Header.vue";
export default {
  components: {
    Paragrafo,
    Titolo,
    Header,
  },
};
</script>

<template>
  <Header></Header>
  <main>
    <Titolo></Titolo>
    <Paragrafo></Paragrafo>
  </main>
</template>

<style scoped>
main {
  margin-top: 100px;
}
</style>
