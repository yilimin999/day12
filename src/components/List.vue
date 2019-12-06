<template>
  <div class="list">
<div class="items" v-for="(item, index) in list" :key="index">
    <div class="img">
        <svg class="icon" aria-hidden="true">
        <use xlink:href="#icon-gouwudai"></use>
        </svg>
    </div>
    <div class="text">
        {{item.content}}
    </div>
</div>
  </div>
</template>

<script>

export default {
    data() {
        return {
            list:[
                {
                    id:1,
                    content:'购物'
                },{
                    id:2,
                    content:'购物'
                },{
                    id:3,
                    content:'购物'
                },{
                    id:4,
                    content:'购物'
                },{
                    id:5,
                    content:'购物'
                },{
                    id:6,
                    content:'购物'
                },{
                    id:7,
                    content:'购物'
                },{
                    id:8,
                    content:'购物'
                }
            ]
        }
    },

}
</script>

<style lang="scss" scoped>
.list{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    align-items: center;
    width: 100%;
    .items{
        display: flex;
        width: 25%;
        height: 150px;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
        img{
            display: flex;
            width: 100px;
            height: 80px;
            svg{
                display: block;
                width: 80%;
                height: 80px;
                use{display: block;
                    width: 80px;
                    height: 80px;
                }
            }
        }
        .text{
            flex: 1;
        }
    }
}
</style>