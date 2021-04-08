<!-- 首页 -->
<template>
  <div class="indexContainer">
    <div class="guitarRound"></div>
    <div class="guitar string1">
      <span class="about">关于</span>
    </div>
    <div class="guitar string2">
      <span class="about">关于</span>
    </div>
    <div class="guitar string3">
      <span class="about">关于</span>
    </div>
    <div class="guitar string4">
      <span class="about">关于</span>
    </div>
    <div class="guitar string5">
      <span class="about">关于</span>
    </div>
    <div class="guitar string6">
      <span class="about">关于</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "Blog",
  setup() {},
};
</script>
<style lang="stylus" scoped>
.indexContainer
  height 100%
  .guitarRound, .guitarRound::after, .guitarRound::before
    position absolute
    border-radius 50%
    box-sizing border-box
    top 50%
    left 50%
    transform translate(-50%, -50%)
  .guitarRound
    height 800px
    width 800px
    background-color #221716
    &:before
      content ''
      display block
      height 810px
      width 810px
      border 2px solid #221716
    &:after
      content ''
      display block
      height 830px
      width 830px
      border 5px solid #221716
  .guitar
    width 100%
    position absolute
    box-shadow 0px 16px 8px 0px
    background-color #feeebe
    background-image linear-gradient(80deg, #867679 50%, transparent 0)
    background-size 2px 5px
    .about
      position absolute
      left 50%
      transform translateY(-50%)
      bottom 0
      color #fff
  .string1
    height 5px
    top 80%
  .string2
    height 4px
    top 68%
  .string3
    height 3px
    top 56%
  .string4
    height 2px
    top 44%
  .string5
    height 1px
    top 32%
  .string6
    height 0.5px
    top 20%
</style>