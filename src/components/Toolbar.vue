<template>
  <div id="toolbar">
    <i class="glyphicon logo"><img src="../assets/logo.png" width="30" height="30"></i>
    <i class="glyphicon glyphicon-plus"></i>
    <i class="glyphicon glyphicon-star"></i>
    <i class="glyphicon glyphicon-remove"></i>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  #toolbar{
    float: left;
    width: 80px;
    height: 100%;
    background-color: #30414D;
    color: #767676;
    padding: 35px 25px 25px 25px;

    .starred {
      color: #F7AE4F;
    }

    i{
      font-size: 30px;
      margin-bottom: 35px;
      cursor: pointer;
      opacity: 0.8;
      transition: opacity 0.5s ease;

      &:hover{
        opacity: 1;
      }
    }
  }
</style>
