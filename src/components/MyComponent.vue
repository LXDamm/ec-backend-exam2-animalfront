<template>
  <div class="my-component">
      <p>Hello</p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "MyComponent",
  props: {
    msg: String,
  },
});
</script>

<style scoped lang="scss">

</style>
