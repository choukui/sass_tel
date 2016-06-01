 #component文件夹的说明
 ###1、-arrow.scss对应是三角箭头样式可以是空心或实心
 ####*  空心的三角箭头
 ####*  一、1：为子元素设定定位上下文，父级设定position:relative;
 ####*  二、假定子元素class="caret",用法 .caret{ left:xx; top:xx; @include caret            (10px,2px,right,orange,orange);}
 ####*  三、参数说明：1.$caret-width三角箭头的外层宽
 ####                 2.$border-width三角箭头的线宽
 ####                 3.$direction三角箭头的方向
 ####                4.$border-color三角箭头的线条颜色
 ####                 5.$background-color三角箭头的中心颜色，如果和$border-color颜色一直则为实心                       三角型*           

