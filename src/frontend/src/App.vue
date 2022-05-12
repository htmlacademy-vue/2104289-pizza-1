<template>
  <div id="app">
    <div class="main">
      <IndexHome />
    </div>
  </div>
</template>

<script>
import IndexHome from "@/views/Index";

export default {
  name: "App",
  components: {
    IndexHome,
  },
};
</script>

<style lang="scss">
@import "~@/assets/scss/app";
</style>
