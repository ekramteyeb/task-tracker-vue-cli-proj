<template>
  <header>
    <h1>{{title}}</h1>
    <Button text="Add Task" color="black"/>
    <Button text="Add Task" color="brown"/>
    <Button text="Add Task" color="green"/>
  </header>
</template>

<script>
import Button from './Button.vue'
export default {
    name: 'HeaderTitle',
    props: {
        title:String
    },
    components: {
        Button,
    }

}

</script>

<style scoped>
    header{
        color:brown;
    }
</style>