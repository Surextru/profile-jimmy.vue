<template>
  <div>
    <h2>{{ name }}</h2>
    <h2>{{ position }}</h2>
  </div>
</template>

<script>
import {aboutme} from "../data"
export default {
  data() {
    return {
      name: aboutme.name,
      position: aboutme.position

    };
  },
};
</script>

<style lang="scss" scoped>
</style>