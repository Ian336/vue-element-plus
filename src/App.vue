<template>
  <el-config-provider namespace="ep">
    <BaseHeader />
    <div class="flex main-container">
      <BaseSide />
      <div w="full" py="4">
        <Logos my="4" />
        <el-button>11111</el-button>
        <!-- <HelloWorld msg="Hello Vue 3 + Element Plus + Vite" /> -->
      </div>
    </div>
  </el-config-provider>
</template>
<script lang="ts" setup>
import { ElButton } from 'element-plus'
// import { useModal } from './modal'
// interface Xu<T extends { a: '' } = Object> {
//   title: 199
//   abc: T
//   dd: T['a']
// }

// function test(params: Xu) {
//   return 1
// }
</script>
<style>
#app {
  text-align: center;
  color: var(--ep-text-color-primary);
}

.main-container {
  height: calc(100vh - var(--ep-menu-item-height) - 3px);
}
</style>
