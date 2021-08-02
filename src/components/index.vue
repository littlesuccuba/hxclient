<template>
    <!-- <h1>well come</h1> -->
    <div>
        <!-- 导航 -->
        <el-row :gutter="20" type="flex" justify="space-around" align="middle" class="nav">
            <!-- 不知道放什么先占着 -->
            <el-col class="nav-item" :span="8" :offset="0">
                
            </el-col>
            <!-- 搜索框 -->
            <el-col :span="8" :offset="0">
                <el-input v-model="content" size="small" @change="viewResults">
                    <el-button slot="append" icon="el-icon-search"></el-button>
                </el-input>
            </el-col>
            <!-- 用户图标或登录 -->
            <el-col :span="8" :offset="0">

            </el-col>
        </el-row>
        
    </div>
</template>

<script>
export default {
    name: 'index',
    data(){
        return {
            content: ''
        }
    },
    methods:{
        viewResults(){

        }
    }
}
</script>

<style scoped>
    /* .nav{
        height: 40px;
    } */
</style>