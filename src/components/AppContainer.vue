<template>
      <i class="container"> <span>{{substruct.name}}</span></i>
</template>

<script>
  export default {
    props:['substruct'],
    name: "app-container"
  }
</script>

<style scoped>
.container {
    grid-row: 2;
    margin: 5px;
    border-right: 2px solid #d8dcdd;
}
.container:last-child {
    border-right: none;
}

</style>
