<template>
      <i class="source" > <span>{{ struct.name }}</span> </i>
</template>

<script>
  export default {
    props: ['struct'],
    name: 'app-source',
    data () {
      return {}
    }
  }
</script>

<style scoped>
.source {
    border-bottom: 2px solid #d8dcdd;
    /* background-color: #ffeaa7; */
}

.source:last-child {
    border-bottom: none;
}
</style>
