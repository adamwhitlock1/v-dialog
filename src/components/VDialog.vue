<template>
  <div>
    <p>dialog here</p>
    <p v-if="title">{{ title }}</p>
  </div>
</template>

<script>
export default {
  name: "VDialog",
  props: {
    title: {
      type: String,
      default: ""
    }
  }
};
</script>
