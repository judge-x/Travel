<template>
	<div class="banner">
		<img class="banner-img" src="//img1.qunarzz.com/sight/p0/1606/5a/5a7ce7e716c8fc97e2.water.jpg_600x330_c6d64c31.jpg" />
		<div class="banner-info">
			<div class="banner-title">碧海银沙（启东恒大世纪旅游城）
			</div>
			<div class="banner-number"><span class="iconfont bannar-icon">
				&#xe9cf;
			</span>39</div>
		</div>
	</div>
</template>

<script>
export default {
	name: 'DetailBanner'
}
</script>

<style lang="stylus" scoped>
.banner
    position: relative
    overflow: hidden
    height: 0
    padding-bottom: 55%
    .banner-img
      width: 100%
    .banner-info
      display: flex
      position: absolute
      left: 0
      right: 0
      bottom: 0
      line-height: .6rem
      color: #fff
      background-image: linear-gradient(top, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.8))
      .banner-tittle
        flex: 1
        font-size: .32rem
        padding: 0 .2rem
      .banner-number
        height: .32rem
        line-height: .32rem
        margin-top: .14rem
        padding: 0 .4rem
        border-radius: .2rem
        background: rgba(0, 0, 0, .8)
        font-size: .24rem
        .banner-icon
          font-size: .24rem
</style>