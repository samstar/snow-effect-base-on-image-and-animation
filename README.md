# snow-effect-base-on-image-and-animation
使用图片配合css3实现下雪效果（来自必应首页图）

原理：雪花透明png图片作为背景图片，4个div绝对定位至容器，背景图片平铺，位置position交错，初始状态top：-100%；
      CSS3动画 从顶部 top:-100% 至 top:0;   设置动画时长和延时，实现下雪效果
