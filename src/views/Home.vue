<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <PxPost msg="user" />
  </div>
</template>

<script>
// @ is an alias to /src
import PxPost from "@/components/PxPost.vue";

export default {
  name: "Home",
  components: {
    PxPost,
  },
};
</script>
