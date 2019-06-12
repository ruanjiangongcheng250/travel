<template>
  <div class="header">
    <div class="header-left">header</div>
    <div class="header-input">header</div>
    <div class="header-right">header</div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang='stylus' scoped>
  .header
    display: flex;
    line-height: 0.86rem;
    background: blue;
    .header-left
      float: left;
    .header-input
      flex: 1
    .header-right
      float: right;
</style>
