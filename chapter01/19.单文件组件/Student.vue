<template>
  <div>
    <h2>学生姓名：{{name}}</h2>
    <h2>学生年龄：{{age}}</h2>
  </div>
</template>

<script>
  export default {
    name: "Student",
    data(){
      return{
        name:"nano",
        age:18
      }
    }
  }
</script>
