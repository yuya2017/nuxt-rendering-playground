<template>
  <div>
    <Header />
    <h1>CSR - クライアントサイドレンダリング</h1>
    <p>このページはクライアントサイドでレンダリングされています。</p>
  </div>
</template>

<script setup>
import Header from '~/components/Header.vue';
</script>

<style scoped>
h1 {
  color: #3498db;
}
</style>
