<template>
<div id="lbox">
    <div class="inputbox">
    <p class="header">
      login
    </p>
    <div class="input-wrapper">
      <div class="border-user">
        用户名<input type="text" name="username" placeholder="请输入用户名">
      </div>
      <div class="border-pwd">
        密码<input type="password" name="password" placeholder="请输入密码">
      </div>
    </div>
    <div class="btn">
      <button>登录</button>
    </div>
    </div>

</div>
</template>

<script>
export default {
    // name: 'LoginBox'
}
</script>

<style scoped>
* {
  padding: 0;
  margin: 0;
}

#lbox {
    position:absolute;
    left: 50%;
    margin-left: -200px;
    top: 50%;
    margin-top: -200px;
    height: 400px;
    width: 400px;
  background-color: #6f6f6f;
  

}
.inputbox {
    position:absolute;
    left: 50%;
    margin-left: -100px;
    top: 50%;
    margin-top: -100px;
    height: 200px;
    width: 200px;

}
p {
    margin-left:auto;
margin-right:auto;
width: 30%;
font-size: 28px;
}
.input-wrapper {
    margin-top: 20px;
    margin-left: 20px;
}
.btn{
    margin-top: 20px;
    margin-left: 80px;
}
.border-pwd {
    margin-top: 2px;
}



</style>