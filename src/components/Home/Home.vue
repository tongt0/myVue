<template>
    <div class="header">
      <div class="back">
        <i class="iconfont icon-fanhui"></i>
      </div>
      <div class="search">
        <a href="">
          <i class="iconfont icon-sousuo"></i>
          <span>输入城市/景点/游玩主题</span>
        </a>
      </div>
      <div class="local">
        <span>北京</span>
        <i class="iconfont icon-sanjiao"></i>
      </div>
    </div>
</template>
s
<script>
export default {
  name: 'Home'
}
</script>

<style scoped lang="stylus">
.header
  display flex;
  height:.88rem;
  background:#00bcd4;
  .back
    color:#fff;
    line-height:.88rem;
    padding:0 .25rem;
    .icon-fanhui
      font-size:.4rem;
  .search
    padding-top:.14rem;
    a
      display block;
      width:6rem;
      height:.6rem;
      background:#fff;
      line-height:.58rem;
      color:#e4e7ea;
      .icon-sousuo
        padding:0 .1rem 0 .2rem;
  .local
    padding:0 .1rem;
    line-height:.84rem;
    color:#fff;

</style>
