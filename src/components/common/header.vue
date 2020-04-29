<template>
    <div class="header">
        <div id="logo">
            <a href="https://www.jd.com/"><img src="@/assets/img/login/logo.png" alt=""></a>
            <span></span>
        </div>
        <a href="https://surveys.jd.com/index.php?r=survey/index/sid/568245/lang/zh-Hans" id="ques"><span></span>登录页面，调查问卷</a>
    </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style scoped>
body {
    font: 12px/150% Arial,Verdana,"\5b8b\4f53";
}
.header {
    padding: 0;
    width: 990px;
    margin: 0 auto;
    
}
#logo {
    padding: 0;
    position: relative;
    width: 300px;
    margin: 10px 0;
    height: 60px;
    float: left;
}
#logo span {
    margin: 0;
    padding: 0;
    display: block;
    width: 110px;
    height: 40px;
    position: absolute;
    right: 0;
    bottom: 0;
    background: url(~@/assets/img/login/l-icon.png) no-repeat;
}
#ques {

margin: 0;
padding: 0;
text-decoration: none;
position: relative;
color: #999;
float: right;
top: 52px;

}
#ques span {
display: inline-block;
width: 18px;
height: 14px;
margin: 0 5px;
background: url(../../assets/img/login/q-icon.png) no-repeat;
overflow: hidden;
vertical-align: middle;
}




</style>