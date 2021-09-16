<template>
  <div class="about">
    <div>This is the about page</div>
    <h2>{{ $route.params.slug }}</h2>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "About",
  components: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img {
  display: initial;
}
</style>
