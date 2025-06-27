<template>
  <div>
    <NuxtLink to="/">首页</NuxtLink>
    <NuxtLink to="/video">视频页</NuxtLink>
    <!-- 路由 -->
    <NuxtPage />

    <van-button type="primary">主要按钮</van-button>
    <van-button type="success">成功按钮</van-button>
    <van-button type="default">默认按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
    <van-button type="warning">警告按钮</van-button>

  </div>
</template>

<script setup lang="ts">
useSeoMeta({
  title: 'bilibili',
  description: 'hhhhh'
})
</script>

<style>
:root {
  --van-primary-color: #FB7299 !important;
}
</style>