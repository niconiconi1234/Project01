张皓捷 19302010021

Github地址：https://github.com/ZhangHJ-qaq/Project01

Github Page地址：https://zhanghj-qaq.github.io/Project01/

项目完成情况：自认为完成了所有的基础功能

Bonus完成情况：

Bonus1：自认为完成了Bonus1。

实现方法：

（1）.用css将每个缩略图的宽高都设置成150px，使用object-Fit=cover属性设置居中裁剪。但这样会丢失部分图片信息。

（2）.如果用户有启用js，则先获取图片的真实宽高，然后用js将"长"和"宽"中较大的一边设置成150px，等比例缩放较短的一边后，再在较短的边旁边用border补上白边。(e.g:如果图片的尺寸是300px(宽)*200px(高)[胖的]，则先将width设置成150px，此时height应等比例缩放成100px，再将图片的border-top和border-bottom各设置成25px，这样图片就在页面中占用了150px乘150px的空间，也没有丢失图片信息。)。如果js不可用，则也可以用（1）中的方法使图片占用固定的空间，不至于使图片变形或页面错位。

Bonus2：整个页面使用flex布局。由于图片缩略图是固定版式的（大小一定），在缩小浏览器宽度时，每一行显示的图片数目会随着浏览器宽度的大小改变。在Browse页如果用户的浏览器宽度较小时，侧边栏会消失，只显示展示图片的盒子。

Bonus3：自认为界面应该不算丑