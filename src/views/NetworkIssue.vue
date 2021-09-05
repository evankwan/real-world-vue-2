<template>
  <div>
    <h1>Uh oh!</h1>
    <h3>Looks like you're experiencing some network issues. Please click the back button and try again</h3>
    <router-link :to="{ name: 'event-list' }">Or go to home page</router-link>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
</style>
