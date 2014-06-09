base-motion（学习记录）
===========

#1.简介

###基础运动，包括匀速运动、弹性运动、拖拽、边界检测、加减速运动等。

#2.详细

###边界检测
####1.检测是否碰撞边界。2.将它放在正确位置。3.然后速度取反。

###运动结构
`````````````
function  constant(target){
  var timeScale = 1000/60;
  if(target.timer){
    clearInterval(target.timer);
  }
  target.timer = serInterval(function(){
    var oldValue.newValue;
    //......
  },timeScale);
}
`````````````

