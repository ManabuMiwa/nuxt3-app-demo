<template>
  <header>
    <h1 class="title">{{ titleName }}</h1>
  </header>
</template>

<script>
export default {
  props: {
    titleName: {
      default: ''
    }
  }
}
</script>

<!-- This style is NG -->
<style>
  .title {
    margin-left: 2rem;
    margin-right: 2rem;
  }
</style>