<script>
import AppBanner from "./components/AppBanner.vue";

export default {
  components: {
    AppBanner,
  },
  data () {
    return {
      title: "my Title"
    }
  }
}

</script>

<template>

  <h1> Hello vue with vite {{  title }} </h1>
  <AppBanner />

</template>

<style>
h1 {
  color: red;
}
</style>