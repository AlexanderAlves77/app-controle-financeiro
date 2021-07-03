<template>
  <div id="app">
    <base-spinner />
    <!-- <router-view /> -->
  </div>
</template>

<!-- prettier-ignore -->
<script>
import BaseSpinner from './components/global/BaseSpinner.vue'

export default {
  name: 'App',
  components: {
    BaseSpinner
  },
  mounted () {
    console.log(this.$firebase)
  }
}
</script>

<style lang="scss"></style>
