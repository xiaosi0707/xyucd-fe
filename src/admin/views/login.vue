<template>
  <div class="login">
  <form class="layui-form" action="">
    <div class="layadmin-user-login-box layadmin-user-login-header">
      <h2>新逸传媒后台管理系统</h2>
    </div>
    <div class="layui-form-item">
      <label class="layui-form-label">输入框</label>
      <div class="layui-input-block">
        <input type="text" name="title" required  lay-verify="required" placeholder="请输入标题" autocomplete="off" class="layui-input">
      </div>
    </div>
    <div class="layui-form-item">
      <label class="layui-form-label">密码框</label>
      <div class="layui-input-inline">
        <input type="password" name="password" required lay-verify="required" placeholder="请输入密码" autocomplete="off" class="layui-input">
      </div>
    </div>
    <div class="layui-form-item">
      <label class="layui-form-label">记住</label>
      <div class="layui-input-block">
        <input type="checkbox" name="switch" lay-skin="switch">
      </div>
    </div>
    <div class="layui-form-item">
      <div class="layui-input-block">
        <button type="reset" class="layui-btn layui-btn-primary">重置</button>
        <button class="layui-btn" lay-submit lay-filter="formDemo">登录</button>
      </div>
    </div>
  </form>
  </div>
</template>

<script>
export default {
  mounted () {
    layui.use('form', function () {
      var form = layui.form
    })
  }
}
</script>

<style>
html, body {
  width: 100%;
  height: 100%;
  background: #f2f2f2;
}
</style>
