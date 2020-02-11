<template>
  <div class="waterfall-wrap" ref="container">
    <div class="piping" ref="pining0"></div>
    <div class="piping" ref="pining1"></div>
    <div class="piping" ref="pining2"></div>
    <div class="piping" ref="pining3"></div>
  </div>
</template>

<script>
export default {
  data() {
    return {}
  },

  props: {
    imgList: {
      type: Array,
      default: () => []
    },
    column: {
      type: Number,
      default: 4
    },
  },

  components: {}
}
</script>

<style rel="stylesheet/scss" lang="scss" scoped></style>
