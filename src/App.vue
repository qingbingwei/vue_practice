<template>
  <div>
    <School></School>
    <Student></Student>
  </div>
</template>

<script>
    import School from './components/SchoolComponenet.vue'
    import Student from './components/StudentComponenet.vue'
    
    export default {
        name:'App',
        components:{
            School,
            Student
        }
    }
</script>

<style>

</style>