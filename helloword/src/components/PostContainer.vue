<script setup>
import PostComponent from './PostComponent.vue';
</script>

<template>
    <div class="post-container">
        <PostComponent/>
        <PostComponent/>
        <PostComponent/>
        <PostComponent/>
    </div>
</template>

<style scoped>
.post-container{
    width: 100%;
    display: flex;
    flex-wrap: wrap;
}
</style>