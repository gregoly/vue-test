<template>
  <b-col v-bind="$attrs" class="p-3">
    <div class="bg-info p-3 h-100">
      <h3 class="text-center">{{ title }}</h3>
      <slot></slot>
    </div>
  </b-col>
</template>
<script>
export default {
  props: {
    title: {
      type: String,
    },
  },
};
</script>
