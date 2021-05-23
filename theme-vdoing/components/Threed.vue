<template>
<h1>3d旋转效果</h1>
  <div class="box1">
    <div id="three">鼠标经过</div>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  },
  setup() {},
};
</script>
<style>
h1{
    text-align: center;
}
#three{
  width: 200px;
  height: 200px;
  margin-left: 200px;
  background: url("https://img1.baidu.com/it/u=2882854598,1294535828&fm=26&fmt=auto&gp=0.jpg") no-repeat;
  transition: all 2s;
}
#three:hover{
  transform: rotateX(180deg) ;
}
.box1{

  perspective: 900px;
}
</style>