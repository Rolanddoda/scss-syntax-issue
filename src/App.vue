<template>
  <div id="app">
    <h1>Example</h1>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style lang="scss">
@use "scss/main";

h1 {
  @include main.heading-style;
}
</style>
