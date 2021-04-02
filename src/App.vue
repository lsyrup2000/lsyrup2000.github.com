<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="stylus">
html, body, #app
  height 100%
#app
  background-color #23da22
  background-image linear-gradient(335deg, #b00 23px, transparent 23px), linear-gradient(155deg, #d00 23px, transparent 23px), linear-gradient(335deg, #b00 23px, transparent 23px), linear-gradient(155deg, #d00 23px, transparent 23px)
  background-size 58px 58px
  background-position 43px 2px, 4px 35px, 29px 31px, 50px 6px
  &:before
    content ''
    display block
    height 100%
    width 100%
    background rgba(255, 255, 255, 0.6)
    position absolute
</style>
