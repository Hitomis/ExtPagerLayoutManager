# ExtPagerLayoutManager

主要针对 [ViewPagerLayoutManager](https://github.com/leochuan/ViewPagerLayoutManager) 做出以下修改：

+ 升级到 AndroidX
+ 修复了连续滑动中，没有及时回收滑出屏幕外的 item 的bug
+ 支持顶部对齐，而不是强制初始化的时候第一个 item 显示在中间的问题
