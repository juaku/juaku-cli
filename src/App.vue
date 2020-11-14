<template lang="pug">
#app
  PxNavigation
  router-view
</template>
<script>
// @ is an alias to /src
import PxNavigation from "@/components/PxNavigation.vue";

export default {
  //name: "Home",
  components: {
    PxNavigation,
  },
};
</script>

<style lang="stylus">
#app
  font-family Avenir, Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  color #2c3e50
  margin-top 60px
</style>
