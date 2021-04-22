<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <div class="navbar-item">
        <span class="title">paint541</span>
      </div>
    </div>
    <div class="navbar-menu">
      <div class="navbar-end">
        <a class="navbar-item is-spaced">
          <span class="icon"><img src="@/assets/svg/gh.svg" /></span>
          <span>GitHub</span>
        </a>
      </div>
    </div>
  </nav>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class TitleBar extends Vue {}
</script>

<style lang="scss">
.icon {
  margin-right: 0.6rem;
}
</style>