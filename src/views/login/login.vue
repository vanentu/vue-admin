<template>
 <div class="flex">
    <el-button type="primary" :icon="Edit" />
    <el-button type="primary" :icon="Share" />
    <el-button type="primary" :icon="Delete" />
    <el-button type="primary" :icon="Search">Search</el-button>
    <el-button type="primary">
      Upload<el-icon class="el-icon--right"><Upload /></el-icon>
    </el-button>
  
  </div>
</template>
<script >
import { Delete, Edit, Search, Share, Upload } from '@element-plus/icons-vue'
// export default{
// name:"home",
// components:{},
// data(){
// return {}
// },
// created(){},
// mounted(){},
// methods:{},
// props:{},
// watch:{},
// };

</script>
<style lang="scss" scoped>
#login {
    height: 50vh;
    background-color: rosybrown
}
</style>    

