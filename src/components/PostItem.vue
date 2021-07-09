<template>
    <div class = "post">
      <div><strong>Название: {{ post.title }}</strong></div>
<div><strong>Описание: {{ post.body }}</strong></div>
    </div>
</template>

<script>
  export default {
    props: {
      post: {
        type: Object,
        required: true,
      }
    }
  }
</script>

<style scoped>

</style>