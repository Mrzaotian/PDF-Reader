<template>
  <el-container style="height: 100vh;">
      <el-aside width="20%">
        <navigation/>
      </el-aside>
      <el-main style="margin:0px;padding:0">
        <navigation/>
      </el-main>
  </el-container>
</template>
<script>
import navigation from '../navigation/navigation.vue'
import content from '../content/content.vue'
export default {
  components:{navigation,content}
} 
</script>
<style>
  body{
    margin: 0px;
  }
</style>