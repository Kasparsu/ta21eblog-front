<script setup>
import MainNav from './components/MainNav.vue';

</script>
<template>
  <MainNav></MainNav>
  <Suspense>
    <RouterView></RouterView>
  </Suspense>
</template>