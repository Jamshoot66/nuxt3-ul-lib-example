<template>
  <div>Hello slot</div>
  <slot></slot>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "HelloSlot",
});
</script>
