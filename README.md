# 记录iOS学习中的零散知识点及好的教程、博客

### 布局相关

* CGRectMake CGRectMake(origin.x，origin.y，size.width. Size.height)在代码中定义矩形。使用CGPointMake(x，y)创建点。CGSize- Make(width，height)创建大小



### UICollectionView 

* 有关UICollectionViewCell的用法，有源码，讲解比较详细：http://blog.csdn.net/u010586842/article/details/48209153 http://blog.csdn.net/eqera/article/details/8134986
http://my.oschina.net/sunqichao/blog/182623#OSC_h4_12
https://onevcat.com/2012/08/advanced-collection-view/
* iOS富文本 http://www.itnose.net/detail/6177538.html
* self.init(frame: CGRectZero)调用父类的构造器

* boundingRectWithSize 返回文本绘制所占据的矩形空间。

* CGRectZero是一个高度和宽度为零、位于(0，0)的矩形常量。需要创建边框但还不确定边框大小或位置时，可以使用此常量

* iOS自定义转场动画http://www.jianshu.com/p/ea0132738057

* UIButton用法 http://00red.com/blog/2015/07/28/teacher-swift-ui-button

