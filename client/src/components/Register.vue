<template>
  <div>
    <h1>Register</h1>
    <h2>Another Heading</h2>
    <input type="email" name="email" placeholder="email" />
    <br />
    <input type="password" name="password" placeholder="password" />
    <br />
    <button></button>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class Register extends Vue {
  data() {
    return {};
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
