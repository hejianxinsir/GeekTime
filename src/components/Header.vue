<template>
  <div class="header">
    <img src="../assets/jike.png" width=120 height=30/>
    <ul>
      <li>讲堂</li>
      <li>部落</li>
      <li>极客大学</li>
      <li>算法训练营里</li>
      <li>Java进阶训练营</li>
      <li>企业版</li>
      <li>极客商城</li>
      <li>兑换中心</li>
      <li>App下载</li>
    </ul>
    <div class="loginAndOut">
      <img src="../assets/search.png" alt="png" width=28 height=28/>
      <span class="login">登录</span>
      <span class="wall"></span>
      <span class="logout">注册</span>
    </div>
  </div>
</template>


<script>
export default {
  name: 'Header'
}
</script>


<style scoped>
.header{
  font-size: 16px;
  padding: 18px 112px;
  border-bottom: 1px solid rgb(234,234,234);
  display: flex;
  align-items: center;
}
.header > ul{
  list-style: none;
  display: flex;
  margin-left: 85px;
  /* margin-right: 30px; */
}
.header > ul > li{
  margin: 0 14px;
}

div.loginAndOut{
  display: flex;
  color: #888;
  align-items: center;
}
div.loginAndOut > img{
  margin: 0 20px 0 30px;
}
div.loginAndOut > .wall{
  border: 1px solid #888;
  height: 14px;
  margin: 0 10px;
  display: inline-block;
}




.icon {
  width: 1em; height: 1em;
  vertical-align: -0.15em;
  fill: currentColor;
  overflow: hidden;
}
</style>