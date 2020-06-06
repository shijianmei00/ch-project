<template>
  <div class="container">
    <div class="left-panel">
      <div class="logo-bg">
        <div class="logo">logo</div>

      </div>
      <ul>
        <li>Section01</li>
        <li>Section02</li>
        <li>Section03</li>
        <li>Section04</li>
        <li>Section05</li>
      </ul>
    </div>
    <nav class="navbar">
      fss
    </nav>
  </div>
</template>

<script>
    export default {
        name: "Home"
    }
</script>

<style scoped lang="less">
  .container{
    background: #f3f3f3;
    width: 100%;
    height: 100%;
    .left-panel{
      width: 270px;
      float: left;
      height: 100%;
      background: #fff;
      box-shadow: 0 0 11px rgba(0, 0, 0, 0.13);
      position: fixed;
      .logo-bg{
        background: #303549;
        height: 80px;
        width: 100%;
        .logo{
          font-size: 45px;
          color: #fff;
        }
      }
    }
    .navbar{
      float: left;
      height: 80px;
      background: #fff;
      box-shadow: 0 0 11px rgba(0, 0, 0, 0.13);
      width: 100%;
    }
  }

</style>
