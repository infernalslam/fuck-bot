<template lang="html">
  <div class="container">
    <div class="row">
      <div class="col-xs-12">
        <span class="label label-default" @click="newTask()">New Task</span>
        <span class="label label-primary" @click="doing()"> mainsteam  <span class="badge"></span> </span>
        <span class="label label-success"> offen <span class="badge"></span></span>
        <!-- <span class="label label-info"> guildline programming <span class="badge"></span></span> -->
        <span class="label label-warning">guildline programming <span class="badge"></span></span>
        <span class="label label-danger">Danger <span class="badge"></span></span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'show',
  props: ['newTask', 'doing']
}
</script>

<style lang="css">
.label {
  cursor: pointer;
}
.badge {
  background-color: #f1ab24;
}
</style>
