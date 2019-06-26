<template>
  <div class="tab">
    <router-link to="/recommend" class="tab-item" tag="div">
      <span>推荐</span>
    </router-link>
    <router-link to="/singer" class="tab-item" tag="div">
      <span>歌手</span>
    </router-link>
    <router-link to="/rank" class="tab-item" tag="div">
      <span>排行</span>
    </router-link>
    <router-link to="/search" class="tab-item" tag="div">
      <span>搜索</span>
    </router-link>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import '@/common/scss/variable.scss';
.tab {
  display: flex;
  width: 100%;
  height: 44px;
  line-height: 44px;
  background-color: $color-theme;

  .tab-item {
    flex: 1;
    text-align: center;

    span {
    }
    &.router-link-active {
      font-weight: bold;
      border-bottom: 2px solid #fff
    }
  }
}
</style>
