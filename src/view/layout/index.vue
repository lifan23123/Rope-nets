<template>
  <div class="layout-nav">nav</div>
  <div class="layout-aside">aside</div>
  <div class="layout-content">content</div>
  <div class="layout-footer">footer</div>
</template>

<script setup lang="ts"></script>

<style lang="less" scoped>
.layout-nav {
  position: fixed;
  background-color: aqua;
}
.layout-aside {
  background-color: brown;
}
.layout-content {
  margin-left: 200px;
  background-color: yellow;
}
.layout-footer {
  position: fixed;
  background-color: orange;
}
</style>
