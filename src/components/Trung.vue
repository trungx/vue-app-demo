<template>
  <div>
    <h1>Contact</h1>
  </div>
</template>
<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class Trung extends Vue {
  @Prop() private trung!: string;
}
</script>
<style lang="scss">
</style>
