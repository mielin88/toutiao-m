<template>
  <div id="app">
    <!-- 路由占位符 -->
    <router-view/>
    <h1>黑马头条</h1>
    <i class="toutiao toutiao-wuwangluo"></i>

    <van-button type="default">默认按钮</van-button>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>
<style lang="less">
</style>
