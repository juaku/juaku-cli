<template lang="pug">
#nav
  router-link(to='/') Home
  |  |
  router-link(to='/about') About
</template>

<script>
export default {
  name: "PxNavigation",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">
h3
  margin 40px 0 0

ul
  list-style-type none
  padding 0

li
  display inline-block
  margin 0 10px

a
  color #42b983
</style>
