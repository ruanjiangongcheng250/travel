<template>
  <div class="header">
    <div class="header-left">
      <span class="iconfont">&#xe624;</span>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe632;</span>
      输入城市/景点/游玩主题
    </div>
    <div class="header-right">
      城市
      <span class="iconfont">&#xe6aa;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang='stylus' scoped>
  @import '../../../assets/varibles.styl';
  .header
    display: flex;
    line-height: 0.86rem;
    background: $bgColor;
    color: #fff;
    .header-left
      width: .64rem;
      float: left;
      text-align: center;
    .header-input
      flex: 1;
      height:.64rem;
      line-height: .64rem;
      margin-left: .12rem;
      background: #fff;
      border-radius: .1rem;
      margin-top: .12rem;
      color: #ccc;
      padding-left: .05rem;
    .header-right
      width: 1.24rem;
      float: right;
      text-align: center;
</style>
