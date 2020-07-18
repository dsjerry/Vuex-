<template>
  <div>
    <add></add>
    <p>---------------------------------------------</p>
    <subb></subb>
  </div>
</template>

<script>
import Add from "./components/Add.vue"
import Sub from "./components/Sub.vue"
export default {
  data() {
    return {}
  },
  components: {
    add: Add,
    subb: Sub
  }
}
</script>

<style></style>
