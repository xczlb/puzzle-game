<template>
  <div>
    {{ name }}
  </div>
</template>

<script>
import { ref } from "vue";
export default {
  setup() {
    const name = ref("love QYX");

    return {
      name,
    };
  },
};
</script>

<style lang="scss" scoped></style>
