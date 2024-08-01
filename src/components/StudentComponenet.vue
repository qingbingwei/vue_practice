<template>
    <div>
        <h2>学生名称：{{stuName}}</h2>
        <h2>学生年龄：{{age}}</h2>
    </div>
</template>

<script>
    //创建student组件
    export default {
        name:'StudentComponent',
        data(){
            return {
                stuName:'z',
                age:19 
            }
        }
    }
</script>
