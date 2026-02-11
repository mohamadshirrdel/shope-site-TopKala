<template>
  <CHeader></CHeader>
  <div class="nav-categories-overlay"></div>
  <!-- end-header -->

  <!-- content-site -->
  <main>
    <div class="main-container">
      <router-view />
    </div>
  </main>
  <!-- content-site -->

  <!-- scroll-top -->
  <div class="btn btn-danger scrolltop">
    <i class="fa fa-angle-up"></i>
    <div class="bg-caver-scroll"></div>
  </div>

  <CFooter></CFooter>
</template>

<script setup>
import CHeader from "./components/CHeader.vue";
import CFooter from "./components/CFooter.vue";
</script>

<style></style>
