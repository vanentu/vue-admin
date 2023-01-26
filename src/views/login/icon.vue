<template>
 <div class="flex">
   
    <!-- 或者独立使用它，不从父级获取属性 -->
    <Edit style="width: 1em; height: 1em; margin-right: 8px"/>
    <el-button type="primary" :icon="Edit" />
    <el-button type="primary" :icon="Share" />
    <el-button type="primary" :icon="Delete" />
    <el-button type="primary">
    <el-icon style="vertical-align: middle">
      <Search />
    </el-icon>
    <span style="vertical-align: middle"> Search </span>
  </el-button>
    <el-button type="primary">
      Upload<el-icon class="el-icon--right"><Upload /></el-icon>
    </el-button>
  <div style="font-size: 20px">
    <!-- 由于SVG图标默认不携带任何属性 -->
    <!-- 你需要直接提供它们 -->
    <Edit style="width: 1em; height: 1em; margin-right: 8px" />
    <Share style="width: 1em; height: 1em; margin-right: 8px" />
    <Delete style="width: 1em; height: 1em; margin-right: 8px" />
    <Search style="width: 1em; height: 1em; margin-right: 8px" />
  </div>
  </div>
</template>
<script >
import { Delete, Edit, Search, Share, Upload } from '@element-plus/icons-vue'
export default{

};

</script>
<style lang="scss" scoped>
#login {
    height: 50vh;
    background-color: rosybrown
}
</style>    

