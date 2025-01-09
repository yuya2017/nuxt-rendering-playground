<template>
  <div>
    <Header />
    <h1>SPA - シングルページアプリケーション</h1>
    <p>このページはクライアントサイドで動的にレンダリングされています。</p>
  </div>
</template>

<script setup>
import Header from '~/components/Header.vue';
</script>

<style scoped>
h1 {
  color: #9b59b6;
}
</style>
