<template>
  <div class="aboutme">
    <h2>{{ name }}</h2>
    <h3>{{ position }}</h3>
    <div class="image">
      <img src="" alt="iamge" />
    </div>
  </div>
</template>

<script>
import { aboutme } from "../data";
export default {
  data() {
    const { name, position, image } = aboutme;
    return {
      name: name,
      position: position,
      image: image,
    };
  },
};
</script>

<style lang="scss" scoped>
</style>