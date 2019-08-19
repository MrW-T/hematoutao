<template>
  <div class="login">
    <el-card class="login-card">
      <div class="titie">
        <img src="../../assets/img/logo_index.png" alt />
      </div>
    </el-card>
  </div>
</template>

<script>
export default {};
</script>

<style lang='less' scoped>
.login {
  width: 100%;
  height: 100vh;
  background-image: url("../../assets/img/login_bg.jpg");
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
  .login-card {
    width: 500px;
    height: 380px;
    .titie {
      text-align: center;
      margin-bottom: 30px;
      img {
        width: 200px;
      }
    }
  }
}
</style>