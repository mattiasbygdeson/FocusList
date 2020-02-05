<template>
  <view class="header">
    <text class="title">
      {{title}}
    </text>
  </view>  
</template>

<script>
export default {
  props: {
    title: String
  }
}
</script>

<style scoped>
.header {
  background-color: #39bf90;
  margin-top: 24px;
  height: 50px;
}
.title {
  margin-top: 4px;
  text-align: center;
  font-size: 28px;
  color: #fff;
  font-weight: bold;
}
</style>