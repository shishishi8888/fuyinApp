<template>
  <div class="box">
      
      <div class="main">
          <img class="a" src="./image/bottom-p-1@2x.png" alt="">
          <p>Here I Am Bryan Adams</p>
          <div>
              <img src="./image/bottom-incon-01@2x.png" alt="">
              <img src="./image/bottom-incon-02@2x.png" alt="">
          </div>
      </div>
  </div>
</template>

<script>
export default {
  data() {
    return {

    }
  },
  methods: {
      
  },
  components: {

  }
}
</script>

<style lang="less" scoped>
@bottomc:rgb(2,89,85);
@mainc:rgb(99,149,138);
    .box{
        margin-top: .98rem;
        position:fixed;
        width: 100%;
        background-color: #fff;
        bottom: 0;
        background-color: @bottomc;
        color: @mainc;
        height: .98rem;
        padding: 0 .32rem;
        .main{
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            font-size: .29rem;
            line-height:.98rem;
            .a{
                position: absolute;
                bottom: .25rem;
                width: .9rem;
            } 
            p{
                margin-left: 1.15rem;
            }
            div{
                // width: 1.20rem;
                display: flex;
                flex-direction: row;
                justify-content: space-between;
                align-items: center;
                img{
                    width: .44rem;
                    &:nth-of-type(1){
                        margin-right: .2rem;
                    }
                }
            }
        }
    }
</style>

