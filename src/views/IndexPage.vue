<template>
  <el-container style="height: 100vh; border: 1px solid #eee">
  <el-aside width="200px" style="background-color: rgb(238, 241, 246)">
    <AsideMenu></AsideMenu>
  </el-aside>
  
  <el-container>
    <el-header style="text-align: right; font-size: 12px">
      <HeaderPage></HeaderPage>
    </el-header>
    
    <el-main>
      <MainPage></MainPage>
    </el-main>
  </el-container>
</el-container>
</template>

<script>
import AsideMenu from './AsideMenu.vue'
import HeaderPage from './HeaderPage.vue'
import MainPage from './MainPage.vue'

export default {
  name: 'IndexPage',
  components: {
    AsideMenu,
    HeaderPage,
    MainPage
  }
}
</script>

<style scoped>
.el-header {
  background-color: #B3C0D1;
  color: #333;
  line-height: 60px;
}
  
.el-aside {
  color: #333;
}
</style>
