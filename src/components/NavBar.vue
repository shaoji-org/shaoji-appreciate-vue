<template>
  <div class="navbar">
    <el-menu class="top-bar" mode="horizontal" router>
      <el-menu-item index="/">ShaoJiOnline</el-menu-item>
      <el-menu-item index="/">首页</el-menu-item>
      <el-menu-item index="/">今日最热</el-menu-item>
      <el-menu-item index="/about">关于我们</el-menu-item>
    </el-menu>
  </div>

</template>

<script>
export default {
  name: "NavBar"
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.top-bar {
  margin-bottom: 20px;
}
</style>