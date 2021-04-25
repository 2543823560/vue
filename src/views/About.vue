<template>
  <div class="about">
    <h1>This is an about page</h1>
    <a id="gg">AAAAA</a>
    <div class="ggg">1323</div>
    <Tab></Tab>
  </div>
</template>
<script>
import Tab from '../components/Tab'
export default {
  components:{
    Tab
  }
}
</script>
<style lang="less" scoped>
 /deep/ .about{
   color: red;
 
}
</style>
