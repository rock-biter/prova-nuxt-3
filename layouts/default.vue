<template>
  <div>
    <nuxt-link to="/">Home</nuxt-link>
    <nuxt-link to="/login">Login</nuxt-link>

    <slot />
  </div>
</template>

<script>
export default {
  setup () {
    

    return {}
  }
}
</script>

<style lang="scss" scoped>

</style>