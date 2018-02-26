<template>
  <div v-show="showFlag" class="food"></div>
</template>

<script type="text/ecmascript-6">
  export default {
    props: {
      food: {
        type: Object
      }
    },
    created() {
      console.log(this.food);
    }
  };
</script>

<style lang="stylus" rel="stylesheet/stylus">
  .food
    position: fixed
    bottom: 48px
    left: 0
    z-index: 30
    width: 100%
    height: 100%
    background: #fff
</style>
