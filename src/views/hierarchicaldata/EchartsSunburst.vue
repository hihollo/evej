<!--  层次数据 树图  -->
<template>
  <div class="echartInfo">
    <treeGraph/>
  </div>
</template>

<script>
import treeGraph from 'components/common/echarts/hierarchicaldata/treeGraph'

export default {
  name: 'EchartsSunburst',
  components: {
    treeGraph
  }
}
</script>

<style scoped>
.echartInfo {
  margin: 20px;
  padding: 20px;
  height: 540px;
  text-align: center;
}
</style>
