<template>
<h3>{{task.text}}</h3>
</template>

<script>

import Task from "./Task"

 export default {
    name: "Task",
    props:{
        task:Object
    }
 }
</script>