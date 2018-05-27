<template>
  <b-row>
    <b-col>
      <task-card/>
    </b-col>
  </b-row>
</template>

<script>
    import TaskCard from '@/components/tasks/TaskCard.vue'
    export default {
        name: "tasks",
        components: {
          TaskCard
        }
    }
</script>

<style scoped>

</style>
