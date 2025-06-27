<script setup lang="ts">
// 通过useFetch获取数据，data是响应式数据，可以直接用于页面渲染
const { data: channelList } = await useFetch('/api/channel')


</script>
<template>
    <div>
        <van-tabs>
            <van-tab v-for="item in channelList" :title="item.name" :key="item.id"></van-tab>
        </van-tabs>
    </div>
</template>
<style scoped></style>