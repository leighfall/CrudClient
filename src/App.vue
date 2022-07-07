<script setup>
import { RouterView } from "vue-router";
import M from "materialize-css";

const vMyDirective = {
  mounted: () => {
    M.AutoInit();
  },
};
</script>

<template>
  <RouterView v-my-directive />
</template>

<style lang="less"></style>
