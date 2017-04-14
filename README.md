# douban
-2017年4月仿照豆瓣网练习Html/css代码
---------------------------
### Q & A

#### 一、div父元素的高度随子元素高度的变化而变化？

1.父元素:after{
  content:"";
  clear:both;
}

2.父元素后添加一个空白div，添加css样式
.div{
  clear:both;
}
