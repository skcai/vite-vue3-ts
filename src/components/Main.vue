<template>
  <el-container>
    <el-header></el-header>
    <el-aside></el-aside>
    <el-main>
      <router-view />
    </el-main>
  </el-container>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({
  name: 'Main',
  props: {},
  setup: () => {}
})
</script>

<style scoped lang="scss"></style>
