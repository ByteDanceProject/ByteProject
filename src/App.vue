<template>
  <div>
    <top></top>
    <middle></middle>
    <foot></foot>
  </div>
</template>

<script>
import top from '@/components/Home/Home-top.vue'
import middle from '@/components/Home/Home-middle.vue'
import foot from './components/Home/Home-foot.vue'
export default {
  components: {
    top,
    middle,
    foot
  }
}
</script>

<style>
</style>
