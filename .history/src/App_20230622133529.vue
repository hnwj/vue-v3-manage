<template>
  app
  <router-view />
</template>
<script setup>
import { onMounted } from 'vue'
import { getListAPI } from '@/api'
const test = async () => {
  const res = await getListAPI()
  console.log(res)
}
onMounted(() => {
  test()
})
</script>
<style lang="less">
</style>
