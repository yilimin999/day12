<template>
  <div class="swiper">
      <van-swipe :autoplay="2000" indicator-color="white">
          <van-swipe-item><img src="https://cn.vuejs.org/images/logo.png" alt=""></van-swipe-item>
          <van-swipe-item><img src="https://cn.vuejs.org/images/logo.png" alt=""></van-swipe-item>
          <van-swipe-item><img src="https://cn.vuejs.org/images/logo.png" alt=""></van-swipe-item>
          <van-swipe-item><img src="https://cn.vuejs.org/images/logo.png" alt=""></van-swipe-item>
      </van-swipe>
  </div>
</template>

<script>
import Vue from 'vue'
import {Swipe,SwipeItem} from 'vant'
Vue.use(Swipe).use(SwipeItem)
export default {

}
</script>

<style lang="scss" scoped>
.swiper{
    border-bottom: 1px solid #000;
}
img{
    width: 100%;
    height: 200px;
}
</style>