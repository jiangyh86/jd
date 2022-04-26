<template>
  <!-- 顶部搜索 -->
  <div class="wrapper">
    <div class="wrapper__position">
      <span class="iconfont">&#xe7f1;</span>
      南京工业职业技术大学计算机与软件技术学院2116班
      <span class="iconfont wrapper__position--side">&#xe683;</span>
    </div>
    <!-- 
  
    <div class="wrapper__search">
      <span class="iconfont">&#xe6b7;</span>
      <span class="search__text">山姆会员商店优惠</span>
    </div>
     banner 
    <div class="wrapper__banner">
      <img
        src="https://s.cn.bing.net/th?id=OHR.ThreeKings_ZH-CN5954425982_1920x1080.jpg&rf=LaDigue_1920x1080.jpg"
        class="banner__img"
      >
    </div> -->

    <!--   搜索   -->
    <div class="wrapper__search">
      <span class="iconfont">&#xe6b7;</span>
      <spam class="search__text">山姆会员商店优惠</spam>
    </div>
    <!-- banner -->
    <div class="wrapper__banner">
      <img
        src="https://wx-login.oss-cn-shanghai.aliyuncs.com/banner.jpeg"
        class="wrapper__banner__img"
      >
    </div>

    <!-- icons九宫格 -->
    <div class="icons">

      <div class="icons__item">

        <img
          src="https://wx-login.oss-cn-shanghai.aliyuncs.com/upload/icon/%E5%8C%BB%E8%8D%AF%E5%81%A5%E5%BA%B7.png"
          alt=""
          class="icons__item__img"
        />

        <p class="icons__item__desc">医疗健康</p>

      </div>

      <div class="icons__item">

        <img
          src="https://wx-login.oss-cn-shanghai.aliyuncs.com/upload/icon/%E5%A4%A7%E7%89%8C%E5%85%8D%E8%BF%90.png"
          class="icons__item__img"
        />

        <p class="icons__item__desc">大牌免运</p>

      </div>

      <div class="icons__item">

        <img
          src="https://wx-login.oss-cn-shanghai.aliyuncs.com/upload/icon/%E5%AE%B6%E5%B1%85.png"
          class="icons__item__img"
        />

        <p class="icons__item__desc">家居</p>

      </div>

      <div class="icons__item">

        <img
          src="https://wx-login.oss-cn-shanghai.aliyuncs.com/upload/icon/%E6%B0%B4%E6%9E%9C%E5%BA%97.png"
          class="icons__item__img"
        />

        <p class="icons__item__desc">水果店</p>

      </div>

      <div class="icons__item">

        <img
          src="https://wx-login.oss-cn-shanghai.aliyuncs.com/upload/icon/%E7%AD%BE%E5%88%B0.png"
          class="icons__item__img"
        />

        <p class="icons__item__desc">签到</p>

      </div>

      <div class="icons__item">

        <img
          src="https://wx-login.oss-cn-shanghai.aliyuncs.com/upload/icon/%E7%BA%A2%E5%8C%85.png"
          alt=""
          class="icons__item__img"
        />

        <p class="icons__item__desc">红包</p>

      </div>

      <div class="icons__item">

        <img
          src="https://wx-login.oss-cn-shanghai.aliyuncs.com/upload/icon/%E8%8F%9C%E5%B8%82%E5%9C%BA.png"
          class="icons__item__img"
        />

        <p class="icons__item__desc">菜市场</p>

      </div>

      <div class="icons__item">

        <img
          src="https://wx-login.oss-cn-shanghai.aliyuncs.com/upload/icon/%E8%9B%8B%E7%B3%95.png"
          class="icons__item__img"
        />

        <p class="icons__item__desc">蛋糕</p>

      </div>

      <div class="icons__item">

        <img
          src="https://wx-login.oss-cn-shanghai.aliyuncs.com/upload/icon/%E8%B6%85%E5%B8%82.png"
          class="icons__item__img"
        />

        <p class="icons__item__desc">超市便利</p>

      </div>

      <div class="icons__item">

        <img
          src="https://wx-login.oss-cn-shanghai.aliyuncs.com/upload/icon/%E9%B2%9C%E8%8A%B1.png"
          class="icons__item__img"
        />

        <p class="icons__item__desc">鲜花</p>

      </div>
    </div>

    <div class="gap">

    </div>
  </div>
  <!-- 底部导航 -->
  <div class="docker">
    <!-- BEM block-element-modifier -->
    <div class="docker__item docker__item--active">
      <div class="iconfont">&#xe696;</div>
      <div class="docker__title">首页</div>
    </div>
    <div class="docker__item">
      <div class="iconfont">&#xe60a;</div>

      <div class="docker__title">购物车</div>
    </div>
    <div class="docker__item">
      <div class="iconfont">&#xe608;</div>

      <div class="docker__title">订单</div>
    </div>
    <div class="docker__item">
      <div class="iconfont">&#xe78b;</div>

      <div class="docker__title">我的</div>
    </div>
  </div>
</template>

<style lang="scss">
@import "./style/iconfont.css";
@import "./style/index.scss";
.wrapper {
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  padding: 0 0.18rem;
  &__position {
    position: relative;
    padding: 0.16rem 0.16rem 0.16rem 0;
    font-size: 0.16rem;
    @include ellipse;
    color: $content-fontcolor;
    // background: green;
    &--side {
      position: absolute;
      top: 0.13rem;
      right: 0;
      font-size: 0.2rem;
    }
  }
  &__search {
    margin-bottom: 0.12rem;
    line-height: 0.32rem;
    background-color: $background-color;
    color: $placeholder-color;
    border-radius: 0.16rem;
    margin-bottom: 0.12rem;
    .iconfont {
      display: inline-block;
      padding: 0 0.12rem 0 0.16rem;
      font-style: 0.2rem;
    }
    &__test {
      display: inline-block;
      font-size: 0.14rem;
    }
  }
  &__banner {
    height: 0;
    // 预留出高度防抖
    padding-bottom: 25.4%;
    &__img {
      width: 100%;
    }
  }
  // .banner {
  //   &__img {
  //     width: 100%;
  //   }
  // }
}

.icons {
  display: flex;
  flex-wrap: wrap;
  margin-top: 0.16rem;
  &__item {
    width: 20%;
    &__img {
      display: block;
      width: 0.4rem;
      height: 0.4rem;
      margin: 0 auto;
    }
    &__desc {
      text-align: center;
      color: $content-fontcolor;
    }
  }
}

.gap {
  margin: 0 -0.18rem;
  height: 0.1rem;
  background-color: $border-color;
}
.docker {
  display: flex;
  position: absolute;
  width: 100%;
  left: 0;
  bottom: 0;
  // background-color: green;
  height: 0.49rem;
  border-top: 0.01rem solid #f1f1f1;
  color: $content-fontcolor;
  &__item {
    flex: 1;
    text-align: center;
    &--active {
      color: $hightlight-color;
    }
    .iconfont {
      margin: 0.07rem 0 0.02rem 0;

      font-size: 0.18rem;
    }
  }
  &__title {
    font-size: 0.2rem;
    transform: scale(0.5, 0.5);
    transform-origin: center top;
  }
}
</style>
