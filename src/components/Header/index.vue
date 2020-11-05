<template>
  <div>
      <!-- 头部栏 -->
      <div class="header">
        <!-- 图片栏 -->
        <div class="logo">
          <img src="./image/header.png" alt="" />
        </div>
        <!-- 导航栏 -->
        <div class="nav">
          <!-- 导航栏左侧 -->
          <ul class="nav-left">
            <li class="nav-left-item">
              <a>供应链</a>
            </li>
            <li class="nav-left-item">
              <a>财务</a>
            </li>
            <li class="nav-left-item">
              <a>人力资源</a>
            </li>
            <li class="nav-left-item">
              <a>价格预测</a>
            </li>
          </ul>
          <!-- 导航栏右侧 -->
          <ul class="nav-right">
            <li class="nav-right-item">
              <span class="iconfont icon-geren"></span>
              <a>张一凡</a>
            </li>
            <li class="line">|</li>
            <li class="nav-right-item">
              <span class="iconfont icon-shezhi"></span>
              <a>注销</a>
            </li>
            <li class="line">|</li>
            <li class="nav-right-item">
              <a class="large">22：30：05</a>
            </li>
            <li class="line">|</li>
            <li class="nav-right-item">
              <img src="./image/yuce.png" />
              <a>价格预测</a>
            </li>
          </ul>
        </div>
      </div>
  </div>
</template>

<script>
  export default {
    name:'Header'
  }
</script>

<style>
/* 头部栏 */
.header {
  width: 1918px;
  height: 107px;
  position: relative;
}
/* 导航栏 */
.header .nav {
  position: absolute;
  left: 778px;
  top: 64px;
}
.header .nav a {
  font-size: 16px;
  color: #3dc0e7;
  text-decoration: none;
  font-weight: bold;
}
/* 导航栏左侧 */
.header .nav .nav-left {
  float: left;
  margin-right: 181px;
}
.header .nav .nav-left .nav-left-item {
  float: left;
  margin-right: 62px;
}
/* 导航栏右侧 */
.header .nav .nav-right {
  float: right;
}
.header .nav .nav-right .nav-right-item {
  box-sizing: border-box;
  float: left;
  width: 115px;
  height: 29px;
}
.header .nav .nav-right .line {
  float: left;
  width: 1px;
  color: #3dc0e7;
  height: 30px;
  margin: 0 24px 0 -12px;
}
.header .nav .nav-right .nav-right-item .iconfont {
  font-size: 16px;
  color: #3dc0e7;
  text-decoration: none;
  font-weight: bold;
  padding-right: 7px;
}
.header .nav .nav-right .nav-right-item img {
  width: 16px;
  height: 16px;
  padding-right: 5px;
}

</style>