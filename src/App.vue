<template>
  <div id="app">
    <Main />
    <Chapter3 />
  </div>
</template>

<script>
import Main from "./components/Main.vue";
import Chapter3 from "./components/Chapter3.vue";

export default {
  name: "App",
  components: {
    Main,
    Chapter3,
  },
};
</script>

<style lang="scss">
// @import '@/assets/scss/variables.scss';
@import '@/assets/scss/styles.scss'
</style>
