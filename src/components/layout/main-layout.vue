<template>
    <div class="fm-layout">
        <MHeader></MHeader>
        <home></home>
    </div>
</template>

<script setup>
import home from '../../pages/home/home.vue';
import MHeader from './header/4m-header.vue';
</script>

<style lang="scss" scoped>
    .fm-layout {
        width: 100%;
        height: 100%;
    }
</style>