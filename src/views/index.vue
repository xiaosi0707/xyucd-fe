<template>
  <div>
    <div style="display: none;" id="banner-mini">
      <mini-banner></mini-banner>
    </div>
    <div style="display: block;" id="banner">
      <xy-banner></xy-banner>
    </div>
    <div class="service">
      <header class="header">咨询服务 <span>SERVICE</span></header>
      <section class="content">
        <dl>
          <dt class="service-icon"></dt>
          <dd>
            <h1>品牌设计</h1>
            <ul>
              <li>
                - 标识logo
              </li>
              <li>
                - 品牌全案
              </li>
              <li>
                - 企业卡通形象
              </li>
              <li>
                - 海报
              </li>
              <li>
                - 企业画册
              </li>
            </ul>
          </dd>
        </dl>
      </section>
      <section class="content">
        <dl>
          <dt class="user-icon"></dt>
          <dd>
            <h1>用户体验</h1>
            <ul>
              <li>
                - 市场调研
              </li>
              <li>
                - 竞品分析
              </li>
              <li>
                - 用户研究
              </li>
              <li>
                - 交互设计
              </li>
              <li>
                - APP界面设计
              </li>
            </ul>
          </dd>
        </dl>
      </section>
      <section class="content">
        <dl>
          <dt class="network-icon"></dt>
          <dd>
            <h1>网络电商</h1>
            <ul>
              <li>
                - 网站设计
              </li>
              <li>
                - 软件界面
              </li>
              <li>
                - 大屏展示
              </li>
              <li>
                - 微信H5
              </li>
              <li>
                - 企业画册
              </li>
            </ul>
          </dd>
        </dl>
      </section>
      <section class="content">
        <dl>
          <dt class="video-icon"></dt>
          <dd>
            <h1>视频制作</h1>
            <ul>
              <li>
                - 视频合成
              </li>
              <li>
                - 特效制作
              </li>
            </ul>
          </dd>
        </dl>
      </section>
    </div>
    <div class="case-index">
      <header class="case-index-header">
        案例 <span>CASE</span>
      </header>
      <section class="case-index-content">
        <ul>
          <li>
            <img src="@/assets/imgs/case1.jpg" alt="">
            <span>微家园</span>
          </li>
          <li>
            <img src="@/assets/imgs/case2.jpg" alt="">
            <span>微家园</span>
          </li>
          <li>
            <img src="@/assets/imgs/case3.jpg" alt="">
            <span>微家园</span>
          </li>
          <li>
            <img src="@/assets/imgs/case4.jpg" alt="">
            <span>微家园</span>
          </li>
          <li>
            <img src="@/assets/imgs/case5.jpg" alt="">
            <span>微家园</span>
          </li>
          <li>
            <img src="@/assets/imgs/case6.jpg" alt="">
            <span>微家园</span>
          </li>
          <li>
            <img src="@/assets/imgs/case7.jpg" alt="">
            <span>微家园</span>
          </li>
          <li>
            <img src="@/assets/imgs/case8.jpg" alt="">
            <span>微家园</span>
          </li>
        </ul>
      </section>
    </div>
    <xy-footer></xy-footer>
  </div>
</template>

<script>
import XyBanner from '../components/banner'
import MiniBanner from '../components/mini-banner'
import XyFooter from '../components/footer'
export default {
  components: {
    XyBanner,
    MiniBanner,
    XyFooter
  },
  mounted () {
    this.$fixed()
  }
}
</script>

<style scoped>

</style>
