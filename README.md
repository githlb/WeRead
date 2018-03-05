你可以认为这是一个遵循Material Design风格的第三方的头条客户端，功能已经相当完备，, 聚合了新闻/段子/图片/视频/头条号内容, 没有广告, 仅仅只有存粹的阅读, 不断完善中, 采用 MVP + RxJava + Retrofit 架构的项目~

包含技术：

基本遵循 Material Design 设计风格
抓包获取今日头条API
使用 Google 官方 MVP 架构
DrawerLayout + NavigationView + BottomNavigationView 搭配使用
RxBus 代替 EventBus 进行组件之间通讯
ViewPager 搭配 Fragment 懒加载
SwipeRefreshLayout 搭配 RecyclerView 下拉刷新上拉加载
自定义 BottomNavigationBehavior 实现上滑隐藏下滑显示
RxJava + Retrofit2 + OkHttp3 做网络请求
OkHttp3 对网络返回内容做缓存, 还有日志、超时重连、头部消息的配置
V层基类的构建, 包括 BaseActivity 和 BaseFragment , 对外提供了相同的接口
使用原生的夜间模式
解决侧滑返回与 View 冲突问题
内置 3 款 Logo, 随意切换
使用 CoordinatorLayout 、 AppBarLayout 、 CollapsingToolbarLayout 、 BottomSheetDialog 等等新控件
使用 7.0 新工具 DiffUtil , 不再无脑 notifyDataSetChanged
使用 ItemTouchHelper 实现今日头条的频道排序、频道移动, 参考 ItemTouchHelperDemo
使用 RxBinding 优雅实现搜索请求
使用 RxLifecycle 绑定 RxJava 生命周期
使用 Travis Cl 持续集成

更加重要的是，作者双11还在更新代码，是个相当不错的学习项目~~

程序仅供学习交流, 不可用于任何商业用途


# WeRead
This is an Android project. WeRead is a Android client of content collection , base on Material Design + MVP + RxJava + Retrofit.You can read something interesting about news,picture,video here. 

# APK
[app-release.apk](https://raw.githubusercontent.com/salecoding/WeRead/master/app/app-release.apk)

## SnapShot
<img src="screenshots/Screenshot_2018-02-25-13-39-17-648_cn.read.png" width="300px"/>
<img src="screenshots/Screenshot_2018-02-25-13-40-38-597_cn.read.png" width="300px"/>
<img src="screenshots/Screenshot_2018-02-25-13-40-47-850_cn.read.png" width="300px"/>
<img src="screenshots/Screenshot_2018-02-25-13-40-55-491_cn.read.png" width="300px"/>
<img src="screenshots/Screenshot_2018-02-25-13-41-08-524_cn.read.png" width="300px"/>
<img src="screenshots/Screenshot_2018-02-25-13-41-18-288_cn.read.png" width="300px"/>
<img src="screenshots/Screenshot_2018-02-25-13-41-33-908_cn.read.png" width="300px"/>
<img src="screenshots/Screenshot_2018-02-25-13-41-39-400_cn.read.png" width="300px"/>
<img src="screenshots/Screenshot_2018-02-25-13-41-46-877_cn.read.png" width="300px"/>
<img src="screenshots/Screenshot_2018-02-25-13-42-19-644_cn.read.png" width="300px"/>
<img src="screenshots/Screenshot_2018-02-25-13-42-28-434_cn.read.png" width="300px"/>


## TODO

- add the channel of video
- something interesting

## Acknowledgements

Thanks to these projects and libraries:

**Libraries**

- [RxJava](https://github.com/ReactiveX/RxJava)
- [RxAndroid](https://github.com/ReactiveX/RxAndroid)
- [Retrofit](https://github.com/square/retrofit)
- [Butter Knife](https://github.com/JakeWharton/butterknife)
- [okhttp3](https://github.com/square/okhttp)
- [greenDAO](https://github.com/greenrobot/greenDAO)

**Design**

- [Material icons](https://design.google.com/icons/)

[Coding](https://coding.net/u/salecoding/p/WeRead/git) 欢迎Star
