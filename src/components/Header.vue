<template>
  <section>
    <el-row>
      <a href="/" class="title">System Conference Deadlines</a>
      <github-button style="padding-left: 5px"></github-button>
      <span v-if="showLatestConf" style="color:#fd3c95;font-weight: bold;">Latest: {{this.showStr}} !!!</span>
    </el-row>
    <el-row class="subtitle">
      Countdowns to system conference deadlines. To add/edit a conference, <a style="color: #666666" href="https://github.com/ccfddl/ccf-deadlines/pulls">send a pull request.</a>
    </el-row>
  </section>
</template>


<style scoped>
.title{
  font-size: 29px;
  color: #2c3e50;
}
.subtitle{
  padding-top: 15px;
  color: #666666;
}
</style>
