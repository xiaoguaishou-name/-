<template>
  <div>
    <!-- 外部容器 -->
    <div class="container">
      <!-- 头部栏 -->
      <Header></Header>
      <!-- 主要内容区 -->
      <div id="main">
        <div class="main-header">
          <!-- 左侧栏 -->
          <div class="left">
            <div class="left-item1">
              <div class="carbon-price">品质特性</div>
              <div class="pie"></div>
            </div>
            <div class="left-item2">
              <div class="evaluate"></div>
              <div class="evaluate"></div>
            </div>
          </div>
          <!-- 中间内容区 -->
          <div class="mainItem">
            <div class="customer">客户排名</div>
            <div class="rectangle"></div>
          </div>
          <!-- 右侧栏 -->
          <div class="right">
            <div class="right-item1">
              <div class="diversification">多元化采购</div>
              <div class="circular"></div>
              <div class="right-item2">
                <div class="drive"></div>
                <div class="drive"></div>
              </div>
            </div>
          </div>

          <!-- 底部栏 -->
          <div class="footer">
            <div class="footer-item">
              <div class="credit">信用评价</div>
              <div class="coverage"></div>
            </div>
            <div class="footer-item">
              <div class="credit">采购均价</div>
              <div class="coverage"></div>
            </div>
            <div class="footer-item">
              <div class="credit">客户类型</div>
              <div class="coverage"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Header from '../../components/Header'
export default {
  name: "Supply",
  components:{
    Header
  }
};
</script>

<style>
/* 外部容器 */
.container {
  width: 1920px;
  height: 1080px;
  background: url(./image/1.png) no-repeat;
}

/* 主要内容区 */
.container #main {
  box-sizing: border-box;
  width: 1890px;
  height: 959px;
  margin: 2px 18px 12px 12px;
  background: url(./image/kuang.png) no-repeat;
}

.container #main .main-header {
  position: relative;
}
/* 左侧栏 */
.container #main .main-header .left {
  position: absolute;
  left: 44px;
  top: 31px;
  width: 453px;
  height: 609px;
}
.container #main .main-header .left .left-item1 {
  width: 453px;
}
.container #main .main-header .left .left-item1 .carbon-price {
  box-sizing: border-box;
  color: #ffffff;
  height: 43px;
  font-size: 18px;
  padding: 13px 0 11px 22px;
  background: url(./image/background\ -right.png) no-repeat;
}
.container #main .main-header .left .left-item1 .pie {
  box-sizing: border-box;
  width: 453px;
  height: 279px;
  border: 1px solid #235464;
}
.container #main .main-header .left .left-item2 {
  width: 453px;
  height: 271px;
  margin-top: 16px;
  display: flex;
  justify-content: space-between;
}
.container #main .main-header .left .left-item2 .evaluate {
  box-sizing: border-box;
  width: 48%;
  border: 1px solid #235464;
}
/* 中间内容区 */
.container #main .main-header .mainItem {
  width: 874px;
  height: 609px;
  position: absolute;
  top: 31px;
  left: 523px;
}
.container #main .main-header .mainItem .customer {
  box-sizing: border-box;
  height: 43px;
  font-size: 18px;
  color: #ffffff;
  padding: 13px 0 11px 22px;
  background: url(./image/background\ -main.png) no-repeat;
}
.container #main .main-header .mainItem .rectangle {
  box-sizing: border-box;
  height: 566px;
  border: 1px solid #235464;
}
/* 右侧栏 */
.container #main .main-header .right {
  width: 453px;
  height: 609px;
  position: absolute;
  left: 1423px;
  top: 31px;
}
.container #main .main-header .right .right-item1 .diversification {
  box-sizing: border-box;
  height: 44px;
  font-size: 18px;
  color: #ffffff;
  padding: 13px 0 11px 22px;
  background: url(./image/background\ -right.png) no-repeat;
}
.container #main .main-header .right .right-item1 .circular {
  box-sizing: border-box;
  width: 453px;
  height: 279px;
  border: 1px solid #235464;
}
.container #main .main-header .right .right-item2 {
  height: 271px;
  margin-top: 16px;
  display: flex;
  justify-content: space-between;
}
.container #main .main-header .right .right-item2 .drive {
  box-sizing: border-box;
  width: 48%;
  border: 1px solid #235464;
}
/* 底部栏 */
.container #main .footer {
  width: 1830px;
  height: 273px;
  position: absolute;
  top: 665px;
  left: 44px;
  display: flex;
  justify-content: space-between;
}
.container #main .footer .footer-item {
  width: 32.8%;
}
.container #main .footer .footer-item .credit {
  box-sizing: border-box;
  width: 100%;
  height: 43px;
  font-size: 18px;
  color: #ffffff;
  padding: 13px 0 11px 22px;
  background: url(./image/background\ -footer.png) no-repeat;
}
.container #main .footer .footer-item .coverage {
  box-sizing: border-box;
  height: 229px;
  border: 1px solid #235464;
}
</style>