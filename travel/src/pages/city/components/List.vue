<template>
  <div class="list" ref="headerwrapper">
    <div>
      <div class="area">
        <div class="title border-topbottom">当前城市</div>
        <div class="button-list">
          <div class="button-wrap">
            <div class="button">北京</div>
          </div>
        </div>
      </div>
      <div class="area">
        <div class="title border-topbottom">热门城市</div>
        <div class="button-list">
          <div class="button-wrap">
            <div class="button">北京</div>
          </div>
          <div class="button-wrap">
            <div class="button">北京</div>
          </div>
          <div class="button-wrap">
            <div class="button">北京</div>
          </div>
          <div class="button-wrap">
            <div class="button">北京</div>
          </div>
        </div>
      </div>
      <div class="area">
        <div class="title border-topbottom">A</div>
        <div class="item-list">
          <div class="item">阿里尔</div>
          <div class="item">阿里尔</div>
          <div class="item">阿里尔</div>
          <div class="item">阿里尔</div>
          <div class="item">阿里尔</div>
        </div>
      </div>
      <div class="area">
        <div class="title border-topbottom">A</div>
        <div class="item-list">
          <div class="item">阿里尔</div>
          <div class="item">阿里尔</div>
          <div class="item">阿里尔</div>
          <div class="item">阿里尔</div>
          <div class="item">阿里尔</div>
        </div>
      </div>
      <div class="area">
        <div class="title border-topbottom">A</div>
        <div class="item-list">
          <div class="item">阿里尔</div>
          <div class="item">阿里尔</div>
          <div class="item">阿里尔</div>
          <div class="item">阿里尔</div>
          <div class="item">阿里尔</div>
        </div>
      </div>
      <div class="area">
        <div class="title border-topbottom">A</div>
        <div class="item-list">
          <div class="item">阿里尔</div>
          <div class="item">阿里尔</div>
          <div class="item">阿里尔</div>
          <div class="item">阿里尔</div>
          <div class="item">阿里尔</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Bscroll from 'better-scroll'

export default {
  name: "CityList",
  mounted () {
    // this.scroll = new Bscroll(this.$refs.headerwrapper)
  }
};
</script>

<style lang="stylus" scoped>
@import '~styles/varibles.styl';

.border-topbottom {
  &:before {
    border-color: #ccc;
  }

  &:after {
    border-color: #ccc;
  }
}

.border-bottom {
  &:before {
    border-color: #ccc;
  }
}

.list {
//   position: absolute;
//   top: 1.58rem;
//   left: 0;
//   right: 0;
//   bottom: 0;
//   overflow: hidden;

  .title {
    line-height: 0.54rem;
    background: #eeeeee;
    padding-left: 0.2rem;
    color: #666;
    font-size: 0.26rem;
  }

  .button-list {
    padding: 0.1rem 0.6rem 0.1rem 0.1rem;
    overflow: hidden;

    .button-wrap {
      width: 33.33%;
      float: left;

      .button {
        padding: 0.1rem;
        text-align: center;
        margin: 0.1rem;
        border: 0.02rem solid #ccc;
        border-radius: 0.06rem;
      }
    }
  }

  .item-list {
    .item {
      line-height: 0.76rem;
      padding-left: 0.2rem;
      border-bottom: 1px solid #ccc;
    }
  }
}
</style>