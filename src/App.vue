<template>
  <div id="app">
    {{msg}}
  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
      msg: 'Hello Word'
    }
  },
  mounted () {
    console.log(this.msg)
  }
}
</script>

<style>
</style>
