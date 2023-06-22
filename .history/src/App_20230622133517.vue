<template>
  app
  <router-view />
</template>
<script setup>
import { onMounted } from 'vue'
import { getListAPI } from '@/api'
const test = async () => {
  const res = await getListAPI()
}
onMounted(() => {

})
</script>
<style lang="less">
</style>
