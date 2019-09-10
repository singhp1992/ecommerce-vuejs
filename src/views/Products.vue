// all products here
<template>
  <div class="products">
    <Title msg="All Products" />
    <Title msg ="Favorites" />
  </div>
</template>

<script>
import Title from "@/components/Title.vue";

export default {
  name: "products",
  components: {
    Title
  }
};
</script>

<style>
</style>