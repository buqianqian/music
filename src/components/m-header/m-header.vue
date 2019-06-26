<template>
  <div class="m-header">
    <div class="icon"></div>
    <div class="text">music</div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import "@/common/scss/variable.scss";
@import "@/common/scss/mixin.scss";

.m-header {
  position: relative;
  height: 44px;
  width: 100%;
  text-align: center;
  background: $color-theme;

  .icon {
    display: inline-block;
    width: 30px;
    height: 32px;
    background: url('logo@2x.png');
    background-size: 30px 32px;
    margin-top: 6px;
  }

  .text {
    display: inline-block;
    vertical-align: top;
    line-height: 44px;
    color: $color-text-l;
  }
}
</style>
