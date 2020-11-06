<template>
  <div>
    <!-- 外部容器 -->
    <div class="container">
      <!-- 头部栏 -->
      <Header></Header>
      <!-- 主要内容区 -->
      <div id="main">
        <div class="main-header clearfix">
          <!-- 左侧栏 -->
          <div class="left">
            <div class="left-item1">
              <div class="carbon-price">品质特性</div>
              <div class="pie">
                <ul>
                  <li>
                    <img src="./image/12.png" alt="" />
                    <span>产品规模</span>
                    <i>2</i>
                  </li>
                  <li>
                    <img src="./image/12.png" alt="" />
                    <span>行业地位</span>
                    <i>0</i>
                  </li>
                  <li>
                    <img src="./image/12.png" alt="" />
                    <span>业务关系持续期</span>
                    <i>5</i>
                  </li>
                  <li>
                    <img src="./image/12.png" alt="" />
                    <span>业务关系强度</span>
                    <i>3</i>
                  </li>
                </ul>
                <div class="quality">
                  <img src="./image/21.png" alt="" />
                  <i>12</i>
                  <span>品质特效</span>
                </div>
              </div>
            </div>
            <div class="left-item2">
              <div class="evaluate">
                <div class="evaluate-header">能力评估</div>
                <div class="evaluate-main">
                  <img src="./image/28.png" alt="" />
                  <div class="desp">
                    <div>
                      <span>40</span>
                    </div>
                    <div>
                      <i>吸货能力</i>
                    </div>
                  </div>
                </div>
              </div>
              <div class="evaluate">
                <div class="evaluate-header">均衡购货评价</div>
                <div class="evaluate-main">
                  <img src="./image/28.png" alt="" />
                  <div class="desp">
                    <div>
                      <span>20</span>
                    </div>
                    <div>
                      <i>均衡购货能力</i>
                    </div>
                  </div>
                </div>
              </div>
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
              <div class="circular">
                <div class="smallLogo">
                  <img src="./image/12.png" alt="">
                  <span>多元化采购能力</span>
                  <i>3</i>
                </div>
              </div>
              <div class="right-item2">
                <div class="drive">
                  <div class="drive-header">带动作用</div>
                  <div class="drive-main">
                    <img src="./image/17.png" alt="" />
                    <span>5</span>
                  </div>
                </div>
                <div class="drive">
                  <div class="drive-header">采购比重</div>
                  <div class="drive-main">
                    <img src="./image/16.png" alt="" />
                    <span>5</span>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- 底部栏 -->
          <div class="footer">
            <div class="footer-item">
              <div class="credit">信用评价</div>
              <div class="coverage">
                <div class="chart">
                  <img src="./image/18.png" alt="" />
                  <i class="numa">15</i>
                  <div class="money">
                    <img src="./image/15.png" alt="" />
                    <span>现金比例</span>
                  </div>
                </div>
                <div class="chart">
                  <img src="./image/18.png" alt="" />
                  <i class="numb">6</i>
                  <div class="group">
                    <img src="./image/13.png" alt="" />
                    <span>配合度</span>
                  </div>
                </div>
              </div>
            </div>
            <div class="footer-item">
              <div class="credit">采购均价</div>
              <div class="coverage"></div>
            </div>
            <div class="footer-item">
              <div class="credit">客户类型</div>
              <div class="coverage">
                <div class="chart">
                  <img src="./image/18.png" alt="" />
                  <i class="numb">5</i>
                  <div class="money">
                    <img src="./image/15.png" alt="" />
                    <span>性质</span>
                  </div>
                </div>
                <div class="chart">
                  <img src="./image/18.png" alt="" />
                  <i class="numb">2</i>
                  <div class="group">
                    <img src="./image/14.png" alt="" />
                    <span>区域</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Header from "../../components/Header";
export default {
  name: "Supply",
  components: {
    Header,
  },
};
</script>

<style>
/* 外部容器 */
.container {
  height: 100%;
  width: 100%;
}

/* 主要内容区 */
.container #main {
  box-sizing: border-box;
  width: 1890px;
  height: 959px;
  margin: 2px 18px 12px 12px;
  background: url(./image/kuang.png) no-repeat;
  background-size: cover;
  margin: 0 auto;
}

/* 清除浮动 */
.container #main.clearfix:after,
.container #main.clearfix:before {
  content: "";
  display: block;
  clear: both;
}

.container #main .main-header {
  width: 100%;
  height: 100%;
  position: relative;
}

.container #main .main-header.clearfix:after,
.container #main .main-header.clearfix:before {
  content: "";
  display: block;
  clear: both;
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
/* 品质特性 */
.container #main .main-header .left .left-item1 .pie {
  box-sizing: border-box;
  width: 453px;
  height: 279px;
  border: 1px solid #235464;
  display: flex;
  justify-content: space-between;
}
.container #main .main-header .left .left-item1 .pie > ul > li:nth-of-type(1) {
  width: 197px;
  height: 52px;
  margin: 19px 0 0 21px;
  text-align: center;
}
.container #main .main-header .left .left-item1 .pie > ul > li {
  position: relative;
  width: 197px;
  height: 52px;
  margin: 11px 0 0 21px;
  text-align: center;
}
.container #main .main-header .left .left-item1 .pie > ul > li img {
  width: 100%;
  height: 100%;
}
.container #main .main-header .left .left-item1 .pie > ul > li span {
  position: absolute;
  left: 16px;
  top: 20px;
  width: 63px;
  height: 16px;
  font-size: 16px;
  font-family: PingFang SC Regular, PingFang SC Regular-Regular;
  color: #fff;
  white-space: nowrap;
}
.container #main .main-header .left .left-item1 .pie > ul > li i {
  position: absolute;
  top: 10px;
  right: 22px;
  font-size: 26px;
  font-family: DIN Alternate Bold, DIN Alternate Bold-Bold;
  /* font-weight: 700; */
  text-align: left;
  color: #1ee3f3;
}
.container #main .main-header .left .left-item1 .pie .quality {
  width: 147px;
  height: 147px;
  position: relative;
  margin: auto;
}
.container #main .main-header .left .left-item1 .pie .quality img {
  width: 147px;
  height: 147px;
}
.container #main .main-header .left .left-item1 .pie .quality i {
  position: absolute;
  top: 44px;
  left: 54px;
  font-size: 26px;
  font-family: DIN Alternate Bold, DIN Alternate Bold-Bold;
  text-align: left;
  color: #1ee3f3;
}
.container #main .main-header .left .left-item1 .pie .quality span {
  position: absolute;
  top: 74px;
  left: 42px;
  font-size: 16px;
  font-family: PingFang SC Regular, PingFang SC Regular-Regular;
  color: #fff;
  white-space: nowrap;
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
.container #main .main-header .left .left-item2 .evaluate .evaluate-header {
  height: 40px;
  font-size: 16px;
  line-height: 40px;
  padding-left: 16px;
  text-align: left;
  color: #ffffff;
  border-bottom: 1px solid #136878;
}
.container #main .main-header .left .left-item2 .evaluate .evaluate-main {
  display: flex;
  justify-content: space-around;
  margin: 52px 0 0 24px;
}
.container #main .main-header .left .left-item2 .evaluate .evaluate-main img {
  width: 89px;
  height: 128px;
}
.container #main .main-header .left .left-item2 .evaluate .evaluate-main .desp {
  white-space: pre-wrap;
  margin: 12px 0 0 6px;
  text-align: left;
}
.container
  #main
  .main-header
  .left
  .left-item2
  .evaluate
  .evaluate-main
  .desp
  > div {
  white-space: pre-wrap;
  margin: 5px 10px 0;
}
.container
  #main
  .main-header
  .left
  .left-item2
  .evaluate
  .evaluate-main
  .desp
  > div
  > span {
  font-size: 28px;
  color: #fff;
}
.container
  #main
  .main-header
  .left
  .left-item2
  .evaluate
  .evaluate-main
  .desp
  > div
  > i {
  font-size: 18px;
  color: #fff;
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
.container #main .main-header .right .right-item1 .circular .smallLogo{
  position: relative;
  width: 227px;
  height: 52px;
  margin: 39px 113px 0;
}
.container #main .main-header .right .right-item1 .circular .smallLogo > img{
  width:100%;
  height:100%;
}
.container #main .main-header .right .right-item1 .circular .smallLogo > span{
  white-space: nowrap;
  position: absolute;
  top:22px;
  left:32px;
  font-size:16px;
  color:#fff;
}
.container #main .main-header .right .right-item1 .circular .smallLogo > i{
  position: absolute;
  top:12px;
  left:182px;
  font-size: 30px;
  color:#32fdf6;
}
.container #main .main-header .right .right-item2 {
  height: 271px;
  margin-top: 16px;
  display: flex;
  justify-content: space-between;
}
.container #main .main-header .right .right-item2 .drive {
  box-sizing: border-box;
  width: 49%;
  border: 1px solid #235464;
}
.container #main .main-header .right .right-item2 .drive .drive-header{
  height: 40px;
  font-size: 16px;
  line-height: 40px;
  padding-left: 16px;
  text-align: left;
  color: #ffffff;
  border-bottom: 1px solid #136878;
}
.container #main .main-header .right .right-item2 .drive .drive-main{
  margin: 10px 49px;
  position: relative;
}
.container #main .main-header .right .right-item2 .drive .drive-main > span{
  position: absolute;
  color:#fff;
  font-size: 30px;
  top:84px;
  left:58px;
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
  display: flex;
  justify-content: space-around;
  box-sizing: border-box;
  height: 229px;
  border: 1px solid #235464;
}
.container #main .footer .footer-item .coverage .chart {
  position: relative;
}
.container #main .footer .footer-item .coverage .chart > img {
  height: 159px;
  width: 138px;
}
.container #main .footer .footer-item .coverage .chart .numa {
  position: absolute;
  top: 50px;
  left: 44px;
  font-size: 42px;
  font-family: DIN Alternate Bold, DIN Alternate Bold-Bold;
  font-weight: bold;
  text-align: left;
  color: #fff;
}
.container #main .footer .footer-item .coverage .chart .numb {
  position: absolute;
  top: 50px;
  left: 56px;
  font-size: 42px;
  font-family: DIN Alternate Bold, DIN Alternate Bold-Bold;
  font-weight: bold;
  text-align: left;
  color: #fff;
}
.container #main .footer .footer-item .coverage .chart .money {
  box-sizing: border-box;
  position: absolute;
  bottom: 21px;
  left: -30px;
  width: 200px;
  height: 47px;
  line-height: 45px;
  border: 1px solid #54e9ff;
  border-radius: 24px;
  text-align: center;
}
.container #main .footer .footer-item .coverage .chart .money > img {
  vertical-align: text-bottom;
  width: 25px;
  height: 24px;
  padding-right: 8px;
}
.container #main .footer .footer-item .coverage .chart .money > span {
  font-size: 18px;
  font-family: PingFang SC Regular, PingFang SC Regular-Regular;
  font-weight: 400;
  color: #fff;
}
.container #main .footer .footer-item .coverage .chart .group {
  box-sizing: border-box;
  position: absolute;
  bottom: 21px;
  left: -30px;
  width: 200px;
  height: 47px;
  line-height: 45px;
  border: 1px solid #54e9ff;
  border-radius: 24px;
  text-align: center;
}
.container #main .footer .footer-item .coverage .chart .group > img {
  vertical-align: text-bottom;
  width: 25px;
  height: 24px;
  padding-right: 8px;
}
.container #main .footer .footer-item .coverage .chart .group > span {
  font-size: 18px;
  font-family: PingFang SC Regular, PingFang SC Regular-Regular;
  font-weight: 400;
  color: #fff;
}
</style>