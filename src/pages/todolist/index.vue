<template>
    <div>
      <h1>vuejs is good</h1>
      <todolist></todolist>
    </div>
</template>

<script>
  import todolist from '@/components/Todolist'
  export default {
    components: {
      // 区分大小写
      todolist
    }
  }
</script>

<style>
h1 {color: red}
</style>
