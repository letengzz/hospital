<script setup lang="ts">

</script>

<template>
<div class="level">
  <h1>医院</h1>
  <div class="content">
    <div class="left">等级:</div>
    <ul class="hospital">
      <li>全部</li>
      <li class="active">三级甲等</li>
      <li>三级乙等</li>
      <li>二级甲等</li>
    </ul>
  </div>
</div>
</template>

<style scoped lang="scss">
.level{
  color: #7f7f7f;
  margin-top: 20px;

  h1{
    font-weight: 900;
    margin: 10px 0px;
  }
  .content{
    display: flex;
    .left{
      margin-right: 10px;
    }
    .hospital{
      display: flex;
      li {
        margin-right: 10px;
        &.active {
          color: #55a6fe;
        }
      }
      li:hover {
        color: #55a6fe;
        cursor: pointer;
      }
    }

  }
}
</style>
