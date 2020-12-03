<template lang='pug'>
UserProfile
</template>

<script>
import UserProfile from './components/UserProfile'
export default {
  name: 'App',
  components: { UserProfile }
}
</script>

<style lang='stylus'>
#app
  font-family Avenir, Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50
  margin-top 60px
  min-height 100vh
  background-color #f3f5fa
</style>
