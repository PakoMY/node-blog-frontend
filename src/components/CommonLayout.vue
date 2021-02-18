<template>
  <div class="container">
    <common-header></common-header>
    <router-view></router-view>
    <common-footer></common-footer>
  </div>
</template>

<script>

import CommonHeader from '@/components/CommonHeader'
import CommonFooter from '@/components/CommonFooter'
export default {
  components:{
    CommonHeader,
    CommonFooter
  } 
};
</script>

<style scoped lang="scss">
  footer {
    margin-top: 80px;
    padding: 15px 0;
    background: #2d2d2d;
    color: #bbb
  }
</style>
