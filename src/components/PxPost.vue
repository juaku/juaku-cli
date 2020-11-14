<template lang="pug">
.hello
  h1 {{ msg }}
  p
    a(href='https://cli.vuejs.org' target='_blank' rel='noopener') name
    | .
  ul
    li
      a(href='/' target='_blank' rel='noopener') juaku.com

</template>

<script>
export default {
  name: "PxPost",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus"></style>
