<template>
  <div class="contact">
    <h1>This is an contact page</h1>
    <Trung trung="hello trung"/>
  </div>
</template>
<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import Trung from "@/components/Trung.vue"; // @ is an alias to /src
@Component({
  components: {
    Trung
  }
})
export default class Contact extends Vue {}
</script>
