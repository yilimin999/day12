<template>
  <div class="tabbar">
      <router-link to="/home">首页</router-link>
      <router-link to="/my">我的</router-link>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.tabbar{
    position: fixed;
    bottom: 0;
    left: 0;
    right: 0;
    width: 100%;
    height: 50px;
    background: skyblue;
    color: aliceblue;
    display: flex;
    justify-content: space-around;
    align-items: center;
    a{
        flex: 1;text-align: center;
        line-height: 50px;
        &.router-link-active{
            background: hotpink;
            color: aliceblue;
        }
    }
}
</style>