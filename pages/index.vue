<template>
  <section class="container">
    <mu-appbar title="小吱社区">
      <mu-text-field icon="search" class="appbar-search-field"  slot="right" hintText="请输入搜索内容"/>
      <mu-flat-button color="white" label="用户中心" slot="right"/>
    </mu-appbar>
    <div class="column-bar"></div>
  </section>
</template>

<style lang="stylus">
.column-bar
  height 50px
  width 100%
  background #ffffff
</style>
