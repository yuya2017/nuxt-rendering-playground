<template>
  <div>
    <Header />
    <h1>SSG - 静的サイト生成</h1>
    <p>このページはビルド時に静的に生成されています。</p>
  </div>
</template>

<script setup>
import Header from '~/components/Header.vue';
</script>

<style scoped>
h1 {
  color: #2ecc71;
}
</style>
