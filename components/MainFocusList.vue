<template>
  <view>
    <text>MainFocusList</text>
    <text>{{tasks[0].title}}</text>
  </view>
</template>

<script>
export default {
  data() {
    return {
      tasks: [
        {
          id: 0,
          title: "Test",
          completed: false,
        }
      ]
    }
  }
}
</script>

<style scoped>

</style>