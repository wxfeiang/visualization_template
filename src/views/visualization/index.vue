<script setup lang="ts">
import autofit from "autofit.js";
import { onMounted } from "vue";
defineOptions({
  name: "Visualization"
});

onMounted(() => {
  autofit.init({
    el: "#page",
    dw: 1920,
    dh: 1080
  });
});
</script>
<template>
  <div id="page" class="bg-slate-500 h-full">大屏幕</div>
</template>
<style lang="scss" scoped>
//@import url(); 引入公共css类
</style>
