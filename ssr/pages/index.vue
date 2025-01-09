<template>
  <div>
    <Header />
    <h1>SSR - サーバーサイドレンダリング</h1>
    <p>このページはサーバーサイドでレンダリングされています。</p>
  </div>
</template>

<script setup>
import Header from '~/components/Header.vue';
</script>

<style scoped>
h1 {
  color: #e74c3c;
}
</style>
