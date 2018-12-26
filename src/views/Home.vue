<template>
  <div class="home"><UMap /></div>
</template>

<script>
// @ is an alias to /src
import UMap from "@/components/UMap.vue";

export default {
  name: "home",
  components: {
    UMap
  }
};
</script>

<style scoped>
.home {
  height: 350px;
  flex: 1 0 auto;
}
</style>
