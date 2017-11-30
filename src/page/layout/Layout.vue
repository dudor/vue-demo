<template>
  <el-container>
  <el-header>Header</el-header>
  <el-container>
    <el-aside width="200px">side</el-aside>
    <el-container>
      <el-main>Main</el-main>
      <el-footer>Footer</el-footer>
    </el-container>
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
