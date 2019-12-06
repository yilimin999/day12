<template>
  <div class="home">
   <Tabbar></Tabbar>
   <Swiper></Swiper>
   <List></List>
  </div>
</template>

<script>
import Tabbar from '../components/Tabbar'
import Swiper from '../components/Swiper'
import List from '../components/List'

export default {
  name: 'home',
  components:{
    Tabbar,Swiper,List
  }
  
}
</script>
