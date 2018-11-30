<template>
  <div class="home">HOME
    <hello></hello>
    <HelloWorld/>
  </div>
</template>

<script>
import Vue from "vue";
import JunyupFirstPlugin from "junyup-first-plugin";
import "junyup-first-plugin/dist/junyup-first-plugin.css";

import HelloWorld from "../components/HelloWorld";

Vue.use(JunyupFirstPlugin);

export default {
  name: "home",
  components: { HelloWorld }
};
</script>

<style scoped lang="sass">
.home
  width: 100vw
  height: 100vh
  background: rgba(0,0,0, 0.1)
</style>
