<template>
  
    <div id="login">
            <v-header/> 
      <v-login-box/>

        <div>
          

        </div>
    </div>  
  
  


</template>

<script>
import Header from '../components/common/header'
import LoginBox from '../components/common/loginbox'

export default {
    // name: Login,
    components: {
        'v-header': Header,
        'v-login-box': LoginBox
    }
}
</script>

<style scoped>
/* #login {
  height: 100%;
  width: 100%;
} */

</style>