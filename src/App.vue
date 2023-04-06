
<template>
  <p class="red">Hello {{ firstName }}!</p>
</template>

<script>
export default {
  data: function () {
    return {
      firstName: "Nestor",
    };
  },
};
</script>

<style>
.red {
  color: blue;
}
</style>