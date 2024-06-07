<template>
  <div>
    <h3>步骤条组件测试</h3>
    <el-steps :space="200" :active="1" finish-status="success">
      <el-step title="已完成"></el-step>
      <el-step title="进行中"></el-step>
      <el-step title="步骤 3"></el-step>
    </el-steps>
  </div>

</template>

<script>
module.exports = {
  data() {
    return {
    }
  }
}
</script>

<style></style>