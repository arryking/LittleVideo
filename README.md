# LittleVideo
Android短视频滑动播放

项目采用了Androidx架构，主要介绍采用RecyclerView配合PagerSnapHelper实现短视频滑动播放内容。

![短视频.gif](https://raw.githubusercontent.com/MickJson/LittleVideo/master/image/%E7%9F%AD%E8%A7%86%E9%A2%91.gif)

PagerSnapHelper可以帮助实现与以下类似的行为 ViewPager。 将RecyclerView和RecyclerView.Adapter的项目都设置为具
有android.view.ViewGroup.LayoutParams＃MATCH_PARENT的高度和宽度，然后使用#attachToRecyclerView（RecyclerView）}
将PagerSnapHelper附加到RecyclerView。


