# HLJNavigationBar

1.提供2种方法处理导航栏隐藏显示
／*
hlj_prefersNavigationBarHidden ,直接hidden导航栏
hlj_navBarBgAlpha,修改透明度
*／
2.导航栏颜色可变
3.导航栏颜色，透明度变化，过渡
4.自定义返回按钮，不使用leftBarButtonItem
5.支持 滑动，点击返回事件的回调
/*
- (BOOL)navigationShouldPop; //是否允许触发返
- (void)navigationDidPop;//pop成功 ，因为侧滑返回可能取消
- (void)navigationPopCancel;//侧滑返回取消
*/
6.支持状态栏颜色智能根据背景色 改变
/*
损失一点空闲的cpu，去做（大家考虑使用）
*/
7.支持动态更新切换NavigationItem
