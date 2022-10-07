<template>
  <div class="report">
    <day />
    <el-card class="box-card">
      <market-data />
    </el-card>
  </div>
</template>

<script>
import day from './compontents/day.vue'
import MarketData from './compontents/marketData.vue'
export default {
  name: 'Report',
  components: { day, MarketData }
}
</script>

<style lang="scss" scoped>
.box-card{
  margin-top: 20px;
}
</style>
