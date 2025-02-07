## 扫描二维码下载APK示例

![apk](https://img-blog.csdnimg.cn/16b3a4447ccb43b9a72280e6b5821cf5.png)

或者 [点击此处链接下载APK](https://www.pgyer.com/QO2p)

# 更新日志

库 | 更新日志
:----|:----
lib-dialog | __NOTE:__ dialog库已迁移到maven仓库，引入方式：<br> __implementation 'io.github.mqcodedev:lib_dialog:1.2.0'__ <br>别忘了在根目录下的build.gradle中声明 mavenCentral()，现在新建项目默认会自动引入<br><br> Jcenter引入方式：<br>~~implementation 'com.ninetripods:lib-dialog:1.1.0'~~<br>未来Jcenter不允许更新版本，墙裂建议使用maven方式引入 <br><br> 优化内容：<br>2019-06-20<br>1、优化dialog默认布局<br>2、修复Activity横竖屏切换导致空指针问题<br>3、优化DialogFragment在Activity onSaveInstanceState()之后调用导致的问题<br>更详细移步：[Android基于DialogFragment封装一个通用的Dialog](https://blog.csdn.net/u013700502/article/details/82777402)


# Blog发布

系列 | 备注
:----|:----
Jetpack系列 | 1、Lifecycle： [Android Jetpack系列之Lifecycle](https://blog.csdn.net/u013700502/article/details/118469311)<br>2、LiveData ：[Android Jetpack系列之LiveData](https://blog.csdn.net/u013700502/article/details/118866217)<br>3、ViewModel：[Android Jetpack系列之ViewModel](https://blog.csdn.net/u013700502/article/details/118962560)<br>4、LiveDataBus：[Android基于LiveData实现消息总线](https://blog.csdn.net/u013700502/article/details/120170790)<br>5、Jetpack MVVM：[Android Jetpack系列之MVVM使用及封装](https://blog.csdn.net/u013700502/article/details/120263741)<br>6、DataStore：[Android Jetpack系列之DataStore](https://blog.csdn.net/u013700502/article/details/121076531)<br>TODO：<br>Navigation
Kotlin | 1、[Kotlin内联函数inline、noinline、crossinline](https://blog.csdn.net/u013700502/article/details/119923024)<br>2、[Kotlin之Flow数据流](https://blog.csdn.net/u013700502/article/details/120526170)<br> TODO
Gradle系列 | 1、Gradle理论与实践一：[Gradle入门](https://blog.csdn.net/u013700502/article/details/85231505 )<br>2、Gradle理论与实践二：[Groovy介绍 ](https://blog.csdn.net/u013700502/article/details/85231600)<br>3、Gradle理论与实践三：[Gradle构建脚本基础](https://blog.csdn.net/u013700502/article/details/85231661)<br>4、Gradle理论与实践四：[自定义Gradle插件](https://blog.csdn.net/u013700502/article/details/85232032)<br>5、[Gradle配置中subprojects和allprojects的区别](https://blog.csdn.net/u013700502/article/details/85231687)<br>6、[添加buid.gradle配置信息，支持多渠道打包](http://www.jianshu.com/p/11484fddda23)
多线程 | **Java & Android:**<br> 1、[Android多线程之HandlerThread](https://blog.csdn.net/u013700502/article/details/76421939) <br> 2、[Android多线程之IntentService](https://blog.csdn.net/u013700502/article/details/76421161) <br>3、[Android中Callable、Future、FutureTask的概念以及几种线程池的使用](https://blog.csdn.net/u013700502/article/details/76421956)<br>4、[Android异步消息处理机制之Handler、Looper、Message](https://blog.csdn.net/u013700502/article/details/62105858) <br>5、[Java多线程之ThreadLocal的使用及源码解析](https://blog.csdn.net/u013700502/article/details/105793313)<br>6、[Java线程基础知识点](https://blog.csdn.net/u013700502/article/details/112130839)<br>7、[JUC系列学习：AbstractQueuedSynchronizer同步器框架及相关实现类](https://blog.csdn.net/u013700502/article/details/112113248)<br>8、[JUC系列学习：线程池Executor框架及其实现ThreadPoolExecutor](https://blog.csdn.net/u013700502/article/details/111828418)<br>9、[JUC系列学习：阻塞队列BlockingQueue介绍及其相关实现ArrayBlockingQueue、LinkedBlockingQueue等的使用及源码分析](https://blog.csdn.net/u013700502/article/details/107478570)<br>10、[JUC系列学习：CountDownLatch、Semaphore、CyclicBarrier的使用及源码解析](https://blog.csdn.net/u013700502/article/details/107478545)<br>11、[JUC系列学习：ReentrantLock的使用、源码解析及与Synchronized的异同](https://blog.csdn.net/u013700502/article/details/107478281)<br>12、[JUC系列学习：ReentrantReadWriteLock的使用及源码解析](https://blog.csdn.net/u013700502/article/details/107478493)<br>13、[Java生产者、消费者模式的几种实现方式](https://blog.csdn.net/u013700502/article/details/107478721)<br>14、[Java多个线程顺序循环执行的几种实现方式](https://blog.csdn.net/u013700502/article/details/107478844)
Android存储 | 1、[Android本地存储之SharedPreferences源码解析](https://blog.csdn.net/u013700502/article/details/53635499)<br>2、DataStore：[Android Jetpack系列之DataStore](https://blog.csdn.net/u013700502/article/details/121076531)<br>3、[Android内存缓存LruCache源码解析](https://blog.csdn.net/u013700502/article/details/75258325)<br>4、[Android使用磁盘缓存DiskLruCache](https://blog.csdn.net/u013700502/article/details/75258257)<br>5、[Android使用LruCache、DiskLruCache实现图片缓存+图片瀑布流](https://blog.csdn.net/u013700502/article/details/75258375)<br>6、[Android本地存储的几种方式](https://blog.csdn.net/u013700502/article/details/79067909)<br>7、[Android数据库Sqlite的基本用法及升级策略](https://blog.csdn.net/u013700502/article/details/78764917)
功能模仿 | 1、[Android使用RecycleView实现魅族手机通讯录界面](https://blog.csdn.net/u013700502/article/details/72818511)<br>2、[Android仿QQ侧滑菜单](https://blog.csdn.net/u013700502/article/details/73162684)<br>3、[Android高仿QQ小红点](https://blog.csdn.net/u013700502/article/details/73478560)
字节码插桩 | 1、[自定义Annotation注解及解析](https://blog.csdn.net/u013700502/article/details/79729882)<br> 2、[Android 采用AOP方式封装6.0权限管理-待升级](https://blog.csdn.net/u013700502/article/details/79748829)
PopupWindow | 1、[Android基于DialogFragment封装一个通用的Dialog](https://blog.csdn.net/u013700502/article/details/82777402)<br>2、[Android封装一个通用的PopupWindow](https://blog.csdn.net/u013700502/article/details/71275093)<br>3、[Android使用WindowManger实现桌面悬浮窗](https://blog.csdn.net/u013700502/article/details/114453653)
其他 | 1、[Java内存结构 & GC回收](https://blog.csdn.net/u013700502/article/details/105352438)<br> 2、[Android嵌套滑动的分析与实践](https://blog.csdn.net/u013700502/article/details/80834819)


## 效果展示
 
 ### Android多线程之HandlerThread、IntentService：
 ![HandlerThread.gif](https://upload-images.jianshu.io/upload_images/587163-8fcc2d6dcdbc7757.gif?imageMogr2/auto-orient/strip)
 ![IntentService.gif](https://upload-images.jianshu.io/upload_images/587163-d36f126c6b0483ff.gif?imageMogr2/auto-orient/strip)
 
 ### Android中几种线程池的使用：
 ![CachedThreadPool.gif](https://upload-images.jianshu.io/upload_images/587163-a7fab256e4437799.gif?imageMogr2/auto-orient/strip)
 ![FixedThreadPool.gif](https://upload-images.jianshu.io/upload_images/587163-81b5fc189abec641.gif?imageMogr2/auto-orient/strip)
 ![SingleThreadExecutor.gif](https://upload-images.jianshu.io/upload_images/587163-3e6c003fa7e4278c.gif?imageMogr2/auto-orient/strip)
 ![Schedule.gif](https://upload-images.jianshu.io/upload_images/587163-b3a74b1e234a25a5.gif?imageMogr2/auto-orient/strip)
 
 ### LruCache、DiskLruCache实现图片缓存，瀑布流：
 ![ImgCache.gif](https://upload-images.jianshu.io/upload_images/587163-a2fd6c97ab4a7811.gif?imageMogr2/auto-orient/strip)
 
 ### 仿QQ侧滑菜单、小红点：
 ![Swipe_menu.gif](https://upload-images.jianshu.io/upload_images/587163-43f6b3f6c0964189.gif?imageMogr2/auto-orient/strip)
 ![qq_point.gif](https://upload-images.jianshu.io/upload_images/587163-7e35275bb608ad32.gif?imageMogr2/auto-orient/strip)
 
 ### 仿魅族通讯录、通用PopupWindow： 
 ![Contacts.gif](https://upload-images.jianshu.io/upload_images/587163-988a21a91ec89901.gif?imageMogr2/auto-orient/strip)
 ![PopupWindow.gif](https://upload-images.jianshu.io/upload_images/587163-2ed25095367ed1b8.gif?imageMogr2/auto-orient/strip)
 
 ### Bundle、AIDL、Messenger、Binder：
 ![intent.gif](https://upload-images.jianshu.io/upload_images/587163-d125bd779e8fb671.gif?imageMogr2/auto-orient/strip)
 ![aidl.gif](https://upload-images.jianshu.io/upload_images/587163-6766165772f98949.gif?imageMogr2/auto-orient/strip)
 ![messenger.gif](https://upload-images.jianshu.io/upload_images/587163-7a26a5bf1c1516f9.gif?imageMogr2/auto-orient/strip)
 ![binder.gif](https://upload-images.jianshu.io/upload_images/587163-d22a95846aafe521.gif?imageMogr2/auto-orient/strip)

 ### 自定义View、ViewGroup
 ![initpintu.jpg](https://upload-images.jianshu.io/upload_images/587163-4ee28b9c0754217f.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


