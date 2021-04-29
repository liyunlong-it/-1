<template>
  <div class="home">
    <div class="header">
      <div><img src="/images/logo.png" alt="" /></div>
      <div>关于我们</div>
      <div class="right">
        <p><van-icon name="contact" /><span>我的</span></p>
        <p><van-icon name="wap-nav" /><span>导航</span></p>
      </div>
    </div>
    <div class="image">
      <img src="/images/1.png" alt="" />
    </div>

    <div class="context">
      <span class="context_header">房先生简介</span>
      <hr />
      <p class="context_font">
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;房先森互联网装修平台由杭州瑞壹网络科技有限公司于2015年成立上线，房先森立足刚需房，专注于家庭装修服务，利用互联网将装修、供应链、金融进行融合，多维度实现用户对设计师、工长、工地、材料等的线上选择体验，房先森以自营的模式真正意义上过滤掉传统家装公司利润，将利润让给业主。房先森与银行合作的专项装修贷款能够解决业主装修资金问题，并以装修套餐＋个性化定制的模式，提供创新型装修服务。
      </p>
    </div>
    <div class="women">
      <p>我们是谁,我们如何与众不同?</p>
      <hr />
      <div class="women_img"><img src="/images/2.png" alt="" /></div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "home",
};
</script>
<style lang="scss" scoped>
.home {
  .header {
    width: 100%;
    height: 5.556rem;
    display: flex;
    border: 1px solid #000;
    justify-content: space-around;
    align-items: center;
    .right {
      width: 1.667rem;
      display: flex;
      justify-content: space-around;
    }
  }
  .context {
    .context_font {
      font-size: 1.111rem;
      color: #333;
    }
    .context_header {
      width: 100%;
      text-align: center;
      hr {
        margin-top: 1.778rem;
      }
    }
  }
  .women_img{
    width: 25rem;
    img{
      width: 100%;
    }
  }
}
</style>
