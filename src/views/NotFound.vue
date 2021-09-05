<template>
  <div>
    <h1>Oops!</h1>
    <h4>The {{ resource }} you're looking for is not here</h4>
    <router-link :to="{ name: 'event-list' }">Back to the home page</router-link>
  </div>
</template>

<script>
export default {
  props: {
    resource: {
      type: String,
      required: true
    }
  }
}
</script>

<style scoped>
</style>
