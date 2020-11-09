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
            <div class="rectangle">
              <div class="info">
                <div class="info-left">
                  <div class="fullName">
                    <span>当前客户信息：王&nbsp;五</span>
                  </div>
                  <div class="firstNum">3</div>
                  <i>,</i>
                  <div class="secondNum">7</div>
                  <div class="thirdNum">1</div>
                  <div class="fourthNum">1</div>
                </div>
                <div class="info-right">
                  <a>填报入口</a>
                </div>
              </div>
              <!-- <el-progress :text-inside="true" :stroke-width="22" :percentage="70" color="#fcb018"></el-progress>
               -->
               <div>
                 <div></div>
                 <div></div>
               </div>
            </div>
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
                <!-- <div class="dash">
                </div> -->
                <ul class="graphical">
                  <li>
                   <span>大料</span> 
                  </li>
                  <li>
                    <span>中料</span>
                  </li>
                  <li>
                    <span>小料</span>
                  </li>
                  <li>
                    <span>焦面</span>
                  </li>
                </ul>
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
            <div class="footer-item2">
              <div class="credit">采购均价</div>
              <div class="coverage2">
                <div class="coverage2-left">
                  <ul class="secondary">
                    <li class="jack">
                     <span>中料</span> 
                    </li>
                    <li class="mary">
                      <i>4532</i>
                    </li>
                    <li class="jack">
                      <span>轻质化煤焦油1</span>
                    </li>
                    <li class="mary">
                      <i>4953</i>
                    </li>
                    <li class="jack">
                      <span>轻质化煤焦油2</span>
                    </li>
                    <li class="mary">
                      <i>3802</i>
                    </li>
                  </ul>
                  <div class="reduce">
                    <img src="./image/27.png" alt="">
                  </div>
                  <div class="price">
                    <div class="price-left">季度销售均价</div>
                    <div class="price-right">0</div>
                  </div>
                </div>
                <div class="coverage2-right">
                  <div class="bery">
                    <img src="./image/29.png" alt="">
                  </div>
                  <div class="cery">
                    <span>5</span>
                  </div>
                  <div class="dery">
                    <img src="./image/23.png" alt="">
                  </div>
                  <div class="eery">
                    <img src="./image/19.png" alt="">
                    <span>3865</span>
                    <i>采购均价</i>
                  </div>
                </div>
              </div>
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
  /* background: #235464; */
  border: 1px solid #235464;
}
.container #main .main-header .mainItem .rectangle .info{
  position: relative;
  display: flex;
  justify-content: space-between;
  margin:40px 21px 0 21px;
}
.container #main .main-header .mainItem .rectangle .info .info-left{
  display: flex;
  font-size: 18px;
  color:#18e3ed;
}
.container #main .main-header .mainItem .rectangle .info .info-left .fullName{
  margin-right:10px;
}
.container #main .main-header .mainItem .rectangle .info .info-left .firstNum{
  position: absolute;
  top:-14px;
  left:178px;
  width: 28px;
  height: 40px;
  line-height: 40px;
  color: #19f1f9;
  font-size: 20px;
  font-weight: bold;
  font-family: DIN Alternate Bold, DIN Alternate Bold-Bold;
  opacity: 0.67;
  border:1px solid #5a9cff;
  text-align: center;
}
.container #main .main-header .mainItem .rectangle .info .info-left > i{
  position: absolute;
  top:9px;
  left:212px;
}
.container #main .main-header .mainItem .rectangle .info .info-left .secondNum{
  position: absolute;
  top:-14px;
  left:218px;
  width: 28px;
  height: 40px;
  line-height: 40px;
  color: #19f1f9;
  font-size: 20px;
  font-weight: bold;
  font-family: DIN Alternate Bold, DIN Alternate Bold-Bold;
  opacity: 0.67;
  border:1px solid #5a9cff;
  text-align: center;
}
.container #main .main-header .mainItem .rectangle .info .info-left .thirdNum{
  position: absolute;
  top:-14px;
  left:252px;
  width: 28px;
  height: 40px;
  line-height: 40px;
  color: #19f1f9;
  font-size: 20px;
  font-weight: bold;
  font-family: DIN Alternate Bold, DIN Alternate Bold-Bold;
  opacity: 0.67;
  border:1px solid #5a9cff;
  text-align: center;
}
.container #main .main-header .mainItem .rectangle .info .info-left .fourthNum{
  position: absolute;
  top:-14px;
  left:286px;
  width: 28px;
  height: 40px;
  line-height: 40px;
  color: #19f1f9;
  font-size: 20px;
  font-weight: bold;
  opacity: 0.67;
  border:1px solid #5a9cff;
  text-align: center;
}
.container #main .main-header .mainItem .rectangle .info .info-right > a{
  text-decoration: underline;
  font-size: 16px;
  color: #18e3ed;
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
  position: relative;
  box-sizing: border-box;
  width: 453px;
  height: 279px;
  border: 1px solid #235464;
}
.container #main .main-header .right .right-item1 .circular .smallLogo{
  position: relative;
  z-index: 3;
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
.container #main .main-header .right .right-item1 .circular .graphical{
  display: flex;
}
.container #main .main-header .right .right-item1 .circular .graphical > li:nth-child(1){
  position: relative;
  width: 84px;
  height: 84px;
  border-radius: 50%;
  border-width:1px;
  border-style: dashed;
  opacity: 0.3;
  border-color: #ffffff;
  margin:80px 21px 0 32px;
}
.container #main .main-header .right .right-item1 .circular .graphical > li:nth-child(1) > span{
  position: absolute;
  text-align: center;
  top:12px;
  left:10px;
  height: 63px;
  line-height: 63px;
  width: 63px;
  font-size: 16px;
  font-family: PingFang SC Semibold, PingFang SC Semibold-Semibold;
  font-weight: bold;
  color:#07233f;
  border-radius: 50%;
  background-color: #fff;
}
.container #main .main-header .right .right-item1 .circular .graphical > li:nth-child(2){
  position: relative;
  width: 84px;
  height: 84px;
  border-radius: 50%;
  border-width:1px;
  border-style: dashed;
  border-color:#fb6f38;
  margin:80px 20px 0 0;
}
.container #main .main-header .right .right-item1 .circular .graphical > li:nth-child(2) > span{
  position: absolute;
  text-align: center;
  top:12px;
  left:10px;
  height: 63px;
  line-height: 63px;
  width: 63px;
  font-size: 16px;
  font-family: PingFang SC Semibold, PingFang SC Semibold-Semibold;
  font-weight: bold;
  color:#07233f;
  border-radius: 50%;
  background-color: #fb6f38;
}
.container #main .main-header .right .right-item1 .circular .graphical > li:nth-child(3){
  position: relative;
  width: 84px;
  height: 84px;
  border-radius: 50%;
  border-width:1px;
  border-style: dashed;
  border-color:#f1e291;
  margin:80px 21px 0 0;
}
.container #main .main-header .right .right-item1 .circular .graphical > li:nth-child(3) > span{
  position: absolute;
  text-align: center;
  top:12px;
  left:10px;
  height: 63px;
  line-height: 63px;
  width: 63px;
  font-size: 16px;
  font-family: PingFang SC Semibold, PingFang SC Semibold-Semibold;
  font-weight: bold;
  color:#07233f;
  border-radius: 50%;
  background-color: #f1e291;
}
.container #main .main-header .right .right-item1 .circular .graphical > li:nth-child(4){
  position: relative;
  width: 84px;
  height: 84px;
  border-radius: 50%;
  border-width:1px;
  border-style: dashed;
  border-color:#62dbe4;
  margin:80px 0 0 0;
}
.container #main .main-header .right .right-item1 .circular .graphical > li:nth-child(4) > span{
  position: absolute;
  text-align: center;
  top:12px;
  left:10px;
  height: 63px;
  line-height: 63px;
  width: 63px;
  font-size: 16px;
  font-family: PingFang SC Semibold, PingFang SC Semibold-Semibold;
  font-weight: bold;
  color:#07233f;
  border-radius: 50%;
  background-color: #62dbe4;
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
.container #main .main-header .right .right-item2 .drive .drive-main > img{
  width:100%;
  height:100%;
}
.container #main .main-header .right .right-item2 .drive .drive-main > span{
  position: absolute;
  color:#fff;
  font-size: 30px;
  top:74px;
  left:54px;
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
  width:530px;
}
.container #main .footer .footer-item2{
  width:729px;
}
/* 底部三栏头部 */
.container #main .footer .footer-item .credit {
  box-sizing: border-box;
  width: 100%;
  height: 43px;
  font-size: 18px;
  color: #ffffff;
  padding: 13px 0 11px 22px;
  background: url(./image/background\ -footer.png) no-repeat;
}
.container #main .footer .footer-item2 .credit {
  box-sizing: border-box;
  width: 100%;
  height: 43px;
  font-size: 18px;
  color: #ffffff;
  padding: 13px 0 11px 22px;
  background: url(./image/30.png) no-repeat;
}
/* 底部左右栏样式 */
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
/* 底部中间栏样式 */
.container #main .footer .footer-item2 .coverage2{
  box-sizing: border-box;
  border: 1px solid #235464;
  display: flex;
}

.container #main .footer .footer-item2 .coverage2 .coverage2-left{
  box-sizing: border-box;
  width: 274px;
  height: 201px;
  border:1px dashed #03feff;
  margin:14px 0 14px 39px;
  display: flex;
  justify-content: space-between;
  border-radius: 6px;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-left .secondary{
  margin:6px 0 6px 6px;
  border:1px solid #03feff;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-left .secondary .jack{
  width: 139px;
  height: 30px;
  font-size: 14px;
  line-height: 30px;
  color:#fff;
  text-align: center;
  background:linear-gradient(#0d96b1 0%, #00b294 100%);
}
.container #main .footer .footer-item2 .coverage2 .coverage2-left .secondary .mary{
  width: 139px;
  height: 30px;
  font-size: 16px;
  line-height: 36px;
  text-align: center;
  color: #03feff;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-left .reduce{
  width: 30px;
  height: 30px;
  margin:auto;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-left .reduce > img{
  width: 100%;
  height: 100%;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-left .price{
  box-sizing: border-box;
  width: 74px;
  height: 124px;
  border: 1px solid #03feff;
  margin:auto;
  display: flex;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-left .price .price-left{
  box-sizing: border-box;
  width: 32px;
  height: 122px;
  text-align: center;
  background: linear-gradient(#0d96b1 0%, #00b294 100%);
  font-size: 14px;
  padding: 10px 9px;
  color:#fff;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-left .price .price-right{
  width:50px;
  height: 122px;
  line-height: 122px;
  text-align: center;
  font-size: 20px;
  color:#fff;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-right{
  /* position: relative; */
  display: flex;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-right .bery{
  width: 30px;
  height: 30px;
  margin: 100px 0 99px 17px;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-right .bery > img{
  width: 100%;
  height: 100%;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-right .cery{
  position: relative;
  box-sizing: border-box;
  width: 50px;
  height: 50px;
  border: 1px solid #32fdf6;
  border-radius: 50%;
  margin:90px 0 89px 17px;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-right .cery > span{
  position: absolute;
  top:9px;
  left:17px;
  font-size: 24px;
  color:#03feff;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-right .dery{
  width: 47px;
  height: 23px;
  margin:104px 0 102px 26px;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-right .dery > img{
  width: 100%;
  height: 100%;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-right .eery{
  position: relative;
  width: 179px;
  height: 179px;
  margin:25px 39px 25px 12px;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-right .eery > img{
  width: 100%;
  height: 100%;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-right .eery > span{
  position: absolute;
  top:60px;
  left:58px;
  font-size: 26px;
  color:#32fdf6;
}
.container #main .footer .footer-item2 .coverage2 .coverage2-right .eery > i{
  position: absolute;
  top:100px;
  left:58px;
  font-size: 16px;
  color:#fff;
}
</style>