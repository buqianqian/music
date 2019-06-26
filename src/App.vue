<template>
  <div id="app">
    <MHeader></MHeader>
    <Tab></Tab>
    <router-view/>
  </div>
</template>

<script>
import MHeader from '@/components/m-header/m-header'
import Tab from '@/components/tab/tab'
export default {
  name: 'App',
  components: {
    MHeader,
    Tab
  }
}
</script>

<style lang="scss" scoped>
@import 'common/scss/index.scss';
#app {
  position: fixed;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  overflow: hidden;
}
</style>
