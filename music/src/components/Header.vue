<template>
    <div class="header">
      <div class="header-left"></div>
      <p class="header-title">Amex音乐</p>
      <div class="header-right"></div>
    </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Header'
}
</script>

<style scoped lang = "scss">
@import "../assets/css/variable";
@import "../assets/css/mixin";

.header{
  width: 100%;
  height: 100px;
  /* background: red; */
  @include bg_color();
  display: flex;
  justify-content: space-between;
  .header-left, .header-right{
    width: 84px;
    height: 84px;
    background: #000;
    margin-top: 8px;
  }
  .header-title{
    text-align: center;
    line-height: 100px;
  }
}
</style>
