<template>
  <div id="note-editor">
    <div class="form-group">
      <input type="text" name="title"
        class="title form-control"
        placeholder="请输入标题">
      <textarea
        name="content"
        class="form-control" row="3" placeholder="请输入正文"></textarea>
    </div>
  </div>
</template>

<script>
  export default {
  }
</script>

<style lang="scss" scoped>
  #note-editor {
    height: 100%;
    margin-left: 380px;

    .form-group{
      height: 50%;
    }

    .title{
      border:0;
    }
    textarea{
      height: 100%;
      border: 0;
      border-radius: 0;
      padding-top: 15px;
    }
  }
</style>
