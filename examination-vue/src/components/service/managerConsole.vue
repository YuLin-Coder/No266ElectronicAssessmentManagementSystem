<template>
    <div style="float:left;">
        <div style="float:left;width:700px;">
            <el-card class="box-card">
                <div class="console">
                    <el-collapse v-model="activeNames">
                        <el-collapse-item title="" name="1">

                        </el-collapse-item>
                        <el-collapse-item title="使用技术" name="2">
                            <div>
                                <el-tag>SpringBoot</el-tag>
                                <el-tag>Vue2.0</el-tag>
                                <el-tag>Elementui</el-tag>
                                <el-tag>jwt</el-tag>
                                <el-tag>MyBatis</el-tag>
                                <el-tag>Mysql</el-tag>
                            </div>
                        </el-collapse-item>
                        <el-collapse-item title="功能介绍" name="3">
                            <div>权限管理：包含菜单管理、用户管理、角色管理、部门管理、用户权限分配。</div>
                            <div>考试管理：包含科目管理、试题管理、试卷管理、考试管理、试卷批改。</div>
                            <div>我的考试：包含在线考试、我的成绩。</div>
                            <div>题型支持：目前暂时支持单选题、判断题、简答题。</div>
                            <div>自动批改：对于单选题和判断题，系统会自动进行批改，简答题需要人工批改。</div>
                        </el-collapse-item>
                    </el-collapse>
                </div>
            </el-card>
        </div>
        <div style="float:left;width:550px;margin-left: 20px;">
            <el-card class="box-card">
                <div class="console">
                    <el-collapse v-model="person">
                        <el-collapse-item title="" name="5">

                            <div>

                            </div>


                        </el-collapse-item>
                        <el-collapse-item title="" name="7">
                            <div>

                            </div>
                        </el-collapse-item>
                    </el-collapse>
                </div>
            </el-card>
        </div>
    </div>
</template>
<script>
export default {
    data() {
        return {
            activeNames: ['1', '2', '3'],
            person: ['5', '6', '7']
        };
    },
    methods: {
    }
}
</script>
<style>
.console .el-collapse-item__header {
    font-size: 16px;
    font-weight: bold;
}

.console .el-collapse-item__content {
    font-size: 15px;
    line-height: 35px;
}
</style>
