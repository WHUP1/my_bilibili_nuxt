<template>
  <div>
    <NuxtLink to="/">首页</NuxtLink>
    <NuxtLink to="/video">视频页</NuxtLink>
    <!-- 路由 -->
    <NuxtPage />
  </div>
</template>

<script setup lang="ts">
useSeoMeta({
  title: 'bilibili',
  description: 'hhhhh'
})
</script>
