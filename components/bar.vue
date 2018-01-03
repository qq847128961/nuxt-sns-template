<template>
  <div class="column-bar">
    <mu-flexbox>
      <mu-flexbox-item>
        <span class="bar-text" @click="toPage('index')">首页</span>
      </mu-flexbox-item>
      <mu-flexbox-item>
        <span class="bar-text" @click="toPage('activity')">活动</span>
      </mu-flexbox-item>
      <mu-flexbox-item>
        <span class="bar-text">动态</span>
      </mu-flexbox-item>
    </mu-flexbox>
  </div>
</template>
<script>
export default {
  methods: {
    toPage (page) {
      this.$router.push({
        'name': page
      })
    }
  }
}
</script>

<style lang="stylus">
.mu-flexbox-item
  cursor pointer
  &:hover
    background #e0e0e0
.bar-text
  line-height 50px
  font-size 18px
</style>
