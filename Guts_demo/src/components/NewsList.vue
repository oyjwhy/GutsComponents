<template>
  <div style="width:80%;margin-left:10%;">
    <!-- <a-button type="primary">Primary</a-button>
    <a-button>Default</a-button>
    <a-button type="dashed">Dashed</a-button>
    <a-button type="danger">Danger</a-button> -->
    <a-card title="News Title">
      <a-col :span="6"><img style="height:200px;" src='https://zos.alipayobjects.com/rmsportal/jkjgkEfvpUPVyRjUImniVslZfWPnJuuZ.png' /></a-col>
      <a-col :span="18">
        
      <a-row>
        <a-col :span="8">日期</a-col>
        <a-col :span="16"></a-col>
      </a-row>

      <a-row>
        <a-col :span="8">撰稿人</a-col>
        <a-col :span="16"></a-col>
      </a-row>

      <a-row>
        <a-col :span="8">新闻摘要</a-col>
        <a-col :span="16"></a-col>
      </a-row>
      </a-col>

    </a-card>

  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
