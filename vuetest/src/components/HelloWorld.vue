<template>
  <div class="hello">
    <el-button type='success' >{{ msg }}</el-button>

    <el-tabs type="border-card" :stretch='false'>
      <el-tab-pane >
        <span slot="label" ><i class="el-icon-date"></i> 我的行程我的行程我的行程</span>
        我的行程
      </el-tab-pane>
      <el-tab-pane label="消息中心">消息中心</el-tab-pane>
      <el-tab-pane label="角色管理">角色管理</el-tab-pane>
      <el-tab-pane label="定时任务补偿">定时任务补偿</el-tab-pane>
    </el-tabs>

    <el-input   placeholder="请输入内容" :tabindex="a" value="1a23456" clearable></el-input>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'ccc',
      a: 'a'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
