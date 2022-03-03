<template>
  <div class="container">
    <div class="section">
      <h1 class="is-size-2">My Project</h1>
      <button
        class="button is-primary"
        @click="handleClick"
      >
        Increment
      </button>
      <p class="red is-size-3 mt-3">{{ myData }}</p>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      myData: 0
    }
  },
  methods: {
    handleClick () {
      this.myData++
    }
  }
}
</script>

<style>
  .red {
    color: red;
  }
</style>
