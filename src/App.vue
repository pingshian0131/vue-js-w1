<script setup>
import ProductPage from "./components/ProductPage.vue";
import ProductDetail from "@/components/ProductDetail.vue";
</script>

<template>
    <div class="container">
    <div class="row py-3">
      <div class="col-md-6">
        <ProductPage />
      </div>
      <div class="col-md-6">
        <ProductDetail />
      </div>
    </div>
    </div>
</template>

<style scoped>
</style>
