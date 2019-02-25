<template>
  <div></div>
</template>
<script lang="ts">
import Vue from "vue";

export default class Sample extends Vue {
  a: string;

  sample_method() {
    return this.a;
  }
}
</script>