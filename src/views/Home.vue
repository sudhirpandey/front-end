<template>
  <span>
    <home-hero></home-hero>
    <product-list></product-list>
  </span>
</template>

<script>
// @ is an alias to /src
import ProductList from '@/components/ProductsList';

export default {
  name: 'home',
  components: {
    HomeHero: () => import('@/components/HomePanel') /* as a promise */,
    ProductList
  }
};
</script>
