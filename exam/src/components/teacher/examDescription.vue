<!-- 实验管理功能介绍 -->
<template>
  <section class="description">
    <p class="title">实验管理功能介绍</p>
    <p class="content">老师发布了实验,学生才可以在主页面看到相应的实验信息。
      有实验安排表以后,才能给该次实验添加题目,对应数据表是exammanage。
      该表保存该次实验,课程名称,实验时间,所属专业,学院等等信息。
    </p>
  </section>
</template>

<style lang="scss" scoped>
.description {
  margin-left: 40px;
  .title {
    font-size: 22px;
    font-weight: 400;
    color: rgb(31, 47, 61);
  }
  .content {
    width: 600px;
    background-color: rgb(236, 248, 255);
    padding: 16px 32px;
    border-radius: 4px;
    border-left: 5px solid rgb(80, 191, 255);
    margin: 20px 0px;
  }
}
</style>
