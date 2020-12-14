<template>
<link rel="stylesheet" href="path/to/font-awesome/css/font-awesome.min.css">
  <div class="body">
    <div id="login">
      <div>
        <div class='account'>
          <span><i class="fa fa-user-circle" aria-hidden="true"></i></span
          ><input class="account-item" placeholder="请输入您的账号" type="text" />
        </div>
        <div class='password'
        ><span>密码：</span><input placeholder="请输入您的密码" type="password" class="password-item" /></div>
        <button id='login'>登录</button>
      </div>
    </div>
  </div>
</template>
<style scoped>
.body {
  width: 50%;
  height: 300px;
  background-color: aqua;
}
.account {
width:60%;
margin:0 auto;
}
input{
    width:50%;
    margin-bottom: 10px;
}
.password{
    width: 60%;
    margin:0 auto;
}
</style>

<script>
export default {
  name: "login",
  components: {},
};
</script>
