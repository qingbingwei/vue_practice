<template>
    <div class="demo">
        <h2>学校名称：{{schoolName}}</h2>
        <h2>学校地址：{{address}}</h2>
    </div>
</template>

<script>
    export default{
        name:'SchoolComponenet',
        data(){
            return {
                schoolName:'cqu',
                address:'cq',
            }
        }
    }

</script>

<style>
    .demo{
        background-color: orange;
    }
</style>