<template>
  <el-container class="wrapper">
  <el-header :style="{'background-color':'#409eff'}">Header</el-header>
  <el-container>
    <el-aside width="200px" class="menu">
       <el-menu default-active="1">
          <el-menu-item index="1">MENU1</el-menu-item>
          <el-menu-item index="2">MENU2</el-menu-item>
          <el-menu-item index="3">MENU3</el-menu-item>
        </el-menu>
    </el-aside>
    <el-main class="content">Main</el-main>
  </el-container>
</el-container>
</template>

<script>
export default {
  name: 'layout'
}
</script>

<style>
.el-container {
    margin-bottom: 40px;
}
</style>
