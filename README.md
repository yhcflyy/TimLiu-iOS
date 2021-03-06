# TimLiu-iOS
========
自己总结的iOS、mac开源项目及库。 

###  目录
- [UI](#UI)
    - [下拉刷新](#下拉刷新)
    - [模糊效果](#模糊效果)
    - [AutoLayout](#AutoLayout)
    - [富文本](#富文本)
    - [图表](#图表)
    - [表相关](#表相关) 
    - [HUD与Toast](#HUD与Toast)
    - [对话框](#对话框)
    - [其他UI](#其他UI)
- [动画](#动画)
    - [侧滑与右滑返回手势](#侧滑与右滑返回手势)
    - [其他动画](#POP动画)
- [网络相关](#网络相关)
    - [网络连接](#网络连接)
    - [网络测试](#网络测试)
    - [图像获取](#图像获取)
    - [网络聊天](#网络聊天)
    - [网络测试](#网络测试)
- [Model](#Model)
- [其他](#其他)
- [数据库](#数据库)
- [缓存处理](#缓存处理)
- [图像浏览及处理](#图像浏览及处理)
- [视频音频处理](#视频音频处理)
- [测试及调试](#测试及调试)
- [响应式框架](#响应式框架)
- [消息推送](#消息推送)
    - [客户端](#客户端)
    - [服务器端](#服务器端)
- [版本新API的Demo](#版本新API的Demo)
- [代码安全](#代码安全)
- [Xcode插件](#Xcode插件)
- [美工资源](#美工资源)
- [开发资源](#开发资源)
    - [开发资料](#开发资料)
    - [他人开源总结](#他人开源总结)
    - [中文开发博客列表](#中文开发博客列表)

========
### 具体内容 =============================
========
#### UI
##### 下拉刷新
* [EGOTableViewPullRefresh](https://github.com/enormego/EGOTableViewPullRefresh) - 最早的下拉刷新控件。
* [SVPullToRefresh](https://github.com/samvermette/SVPullToRefresh) - 下拉刷新控件。 
* [MJRefresh](https://github.com/CoderMJLee/MJRefresh) - 仅需一行代码就可以为UITableView或者CollectionView加上下拉刷新或者上拉刷新功能。可以自定义上下拉刷新的文字说明。具体使用看“使用方法”。 
* [CBStoreHouseRefreshControl](https://github.com/coolbeet/CBStoreHouseRefreshControl) - 一个效果很酷炫的下拉刷新控件。
* [BreakOutToRefresh](https://github.com/dasdom/BreakOutToRefresh) - 一个下拉刷新打砖块的开源 Swift 库。

##### 模糊效果
 * [FXBlurView](https://github.com/nicklockwood/FXBlurView) -be 支持iOS5.0以上版本，支持静态、动态模糊效果，继承与UIView的模糊特效。
 * [VVBlurPresentation](https://github.com/onevcat/VVBlurPresentation) -很简单易用的在原来viewconntroller基础上做模糊，然后present新的viewcontroller的。

##### AutoLayout
 * [Masonry](https://github.com/Masonry/Masonry) - Masonry是一个轻量级的布局框架，拥有自己的描述语法，采用更优雅的链式语法封装自动布局，简洁明了并具有高可读性（ [使用介绍1](http://adad184.com/2014/09/28/use-masonry-to-quick-solve-autolayout/)  [使用介绍2](http://ios.jobbole.com/81483/)）。
 
 * [Snappy](https://github.com/Masonry/Snappy) - 
 * [PureLayout](https://github.com/smileyborg/PureLayout) - 
 * [Cartography](https://github.com/robb/Cartography) - 

##### 富文本
 * [RTLabel](https://github.com/honcheng/RTLabel) - 富文本
 * [TTTAttributedLabel](https://github.com/mattt/TTTAttributedLabel) - 一个文字视图开源组件，是UILabel的替代元件，可以以简单的方式展现渲染的属性字符串。另外，还支持链接植入，不管是手动还是使用UIDataDetectorTypes自动把电话号码、事件、地址以及其他信息变成链接。[用TTTAttributedLabel创建变化丰富的UILabel](http://blog.csdn.net/prevention/article/details/9998575)
* [FXLabel](https://github.com/nicklockwood/FXLabel) - FXLabel是一个功能强大使用简单的类库，通过提供一个子类改进了标准的UILabel组件，为字体增加了阴影、内阴影和渐变色等，可以被用在任何标准的UILabel中。FXLabel还提供了更多控件，可以对字体行距、字体间距等进行调整。


##### 图表
 * [PNChart](https://github.com/kevinzhow/PNChart) - 国内开源作者，动态的图表。

##### 表相关
 * [SWTableViewCell](https://github.com/onevcat/SWTableViewCell) - 国内开源作者，带很多手势的表单元格。
 * [MCSwipeTableViewCell](https://github.com/alikaragoz/MCSwipeTableViewCell) - 带很多手势的表单元格。
 * [TMQuiltView](https://github.com/1000Memories/TMQuiltView) - 瀑布流。
 * [XLForm](https://github.com/xmartlabs/XLForm) - 很多表格类的table,写法更高冷一点，推荐使用。 
 * [RETableViewManager](https://github.com/romaonthego/RETableViewManager) - 可以十分方便地生成各种样式、各种功能的TableView。只要开发者能想到的列表效果或者功能，都可以利用这份代码迅速编写出来。比如，之前要实现一个填写各种资料的列表，可能需要很多代码，现在只需要几行代码就可以实现。 



##### HUD与Toast
 * [MBProgressHUD](https://github.com/jdg/MBProgressHUD) - 最多人用的loading。
 * [SVProgressHUD](https://github.com/TransitApp/SVProgressHUD) - SVProgressHUD的loading。
 * [ProgressHUD](https://github.com/relatedcode/ProgressHUD) - ProgressHUD的loading，使用最简单。

##### 对话框
* [WCAlertView](https://github.com/m1entus/WCAlertView) - 自定义的对话框。
* [IOS7AlertView](https://github.com/wimagguc/ios-custom-alertview) - IOS7AlertView的对话框。
* [AMSmoothAlert](https://github.com/mtonio91/AMSmoothAlert) - 动画效果不错，最多star，但不支持arm64。
* [DQAlertView](https://github.com/dinhquan/DQAlertView) - 扁平化的样式不错。
* 

##### 其他UI
 * [AwesomeMenu](https://github.com/levey/AwesomeMenu) - 最多人用的Path菜单。
 * [TwitterPaggingViewer](https://github.com/xhzengAIB/TwitterPaggingViewer)  - 多个Tableview，左右滑动。
 * [CircularProgressControl](https://github.com/carantes/CircularProgressControl) - Circular Progress Control using CAShapeLayer ，环形进度控制条。
 * [XLPagerTabStrip](https://github.com/xmartlabs/XLPagerTabStrip) - 做的很棒的iOS下的PagerTabStrip。 


========
#### 动画
##### 侧滑与右滑返回手势
 * [SloppySwiper](https://github.com/fastred/SloppySwiper) - iOS系统自带的UINavigationController要7.0才支持，但不过该手势只能从屏幕左侧边缘识别，如果要扩大到整个屏幕范围怎么办？配合一个SloppySwiper无需代码就可以轻松实现。此库支持iOS5.0以上版本（另外：Nav的title滑动不明显，本人写了2个类似的控件）
 * [GHSidebarNav](https://github.com/gresrun/GHSidebarNav) - 现在比较流行使用侧开菜单设计。试了不少控件，感觉GHSidebarNav最成熟，尤其对纯代码创建的界面兼容性最好。[在Storyboard中使用GHSidebarNav侧开菜单控件](http://www.cnblogs.com/zyl910/archive/2013/06/14/ios_storyboard_sidemenu.html)。
 * [animated-tab-bar](https://github.com/Ramotion/animated-tab-bar) - 让TabBar items能显示萌萌的动画。


##### 其他动画
 * [popping](https://github.com/schneiderandre/popping) - popping是一个POP 使用实例工程 
 * [SinaMenuView](https://github.com/xhzengAIB/SinaMenuView) - 用POP动画引擎写的Sina微博的Menu菜单。
 * [ZQLRotateMenu](https://github.com/pingguo-zangqilong/ZQLRotateMenu) - 这是一个旋转视图的选择器。



========
#### 网络相关
##### 网络连接
* [AFNetworking](https://github.com/AFNetworking/AFNetworking) - ASI不升级以后，最多人用的网络连接开源库。
* [Alamofire](https://github.com/Alamofire/Alamofire) - Alamofire是AFNetworking的作者mattt新写的网络请求的swift库。
* [YTKNetwork](https://github.com/yuantiku/YTKNetwork) - 是基于 AFNetworking 封装的 iOS 网络库，提供了更高层次的网络访问抽象。相比 AFNetworking，YTKNetwork 提供了以下更高级的功能：按时间或版本号缓存网络请求内容、检查返回 JSON 内容的合法性、文件的断点续传、批量的网络请求发送、filter和插件机制等。
* [LxFTPRequest](https://github.com/DeveloperLx/LxFTPRequest) - 支持获取FTP服务器资源列表，下载/上传文件，创建/销毁ftp服务器文件/目录，以及下载断点续传，下载/上传进度，自动判断地址格式合法性跟踪等功能！国人开发，QQ：349124555。
* [WTRequestCenter](https://github.com/swtlovewtt/WTRequestCenter) - 方便缓存的请求库，提供了方便的HTTP请求方法，传入请求url和参数，返回成功和失败的回调。 UIKit扩展提供了许多不错的方法，快速缓存图片，图片查看，缩放功能， 颜色创建，设备UUID，网页缓存，数据缓存等功能。 无需任何import和配置，目前实现了基础需求。
* [MMWormhole](https://github.com/mutualmobile/MMWormhole) - Message passing between iOS apps and extensions 2个iOS设备之间通信。 


##### 图像获取
* [SDWebImage](https://github.com/rs/SDWebImage) - SDWebImage 网络图片获取及缓存处理。

##### 网络聊天
* [XMPPFramework](https://github.com/robbiehanson/XMPPFramework) - XMPPFramework openfire聊天。
* [环信](http://www.easemob.com/) - 给开发者更稳定IM云功能。8200万用户考验，好用！（暂无及时语音、视频通话）
* [融云](http://www.rongcloud.cn/) - 即时通讯云服务提供商。（暂无及时语音、视频通话）
* [容联云通讯](http://www.yuntongxun.com) - 提供基于互联网通话,视频会议,呼叫中心/IVR,IM等通讯服务。
* [chatsecure](https://chatsecure.org/) - 基于XMPP的iphone、android加密式聊天软件。 [iOS代码1](https://github.com/chrisballinger/Off-the-Record-iOS)，[iOS代码2](https://github.com/chrisballinger/ChatSecure-iOS)， [iOS中文版](http://www.cocoachina.com/bbs/read.php?tid=153156)。
 

##### 网络测试
* [Reachability](https://github.com/tonymillion/Reachability) - 苹果提供过一个Reachability类，用于检测网络状态。但是该类由于年代久远，并不支持ARC。该项目旨在提供一个苹果的Reachability类的替代品，支持ARC和block的使用方式。

========
#### Model
* [JSONKit](https://github.com/johnezang/JSONKit) - JSONKit库是非常简单易用而且效率又比较高的，重要的JSONKit适用于ios 5.0以下的版本,使用JSONKit库来解析json文件，只需要下载JSONKit.h 和JSONKit.m添加到工程中；然后加入libz.dylib即可。
* [JSONModel](https://github.com/icanzilb/JSONModel) - 解析服务器返回的Json数据的库,[JSONModel源码解析一](http://www.jianshu.com/p/3d795ea37835)。
* [Mantle](https://github.com/Mantle/Mantle) - Mantle主要用来将JSON数据模型化为OC对象, 大系统中使用。[为什么选择Mantle](http://www.iwangke.me/2014/10/13/Why-Changba-iOS-choose-Mantle/)。
* [RFJModel](https://github.com/refusebt/RFJModel) - RFJModel是一个IOS类库，可以将JSON字典自动装填到OBJC对象。相比JSONModel有一些非常好的特性，使用上也比较简单。

========
#### 其他
* [DateTimeKit](https://github.com/exsortis/DateTimeKit) - 一个超赞的时间处理的库，Joda-Time ！ 他能帮你轻松处理时区，处理时间加减，计算到期时间等等场景下的问题。


========
#### 数据库
* [FMDB](https://github.com/ccgus/fmdb) - sqlite的工具。
* [GXDatabaseUtils](https://github.com/Gerry1218/GXDatabaseUtils) - 在FMDB基础上的工具。
* [realm-cocoa](https://github.com/realm/realm-cocoa) - Realm是一个真正为移动设备打造的数据库，同时支持Objective-C和Swfit。Realm宣称其相比Sqlite，在移动设备上有着更好的性能表现。

========
#### 缓存处理
* [YTKKeyValueStore](https://github.com/yuantiku/YTKKeyValueStore) - Key-Value存储工具类，[说明](http://tangqiaoboy.gitcafe.io/blog/2014/10/03/opensouce-a-key-value-storage-tool/)。

========
#### 图像浏览及处理
* [FLAnimatedImage](https://github.com/liric28/FLAnimatedImage) - gif播放处理的工具。
* [Reader](https://github.com/vfr/Reader) - 项目能够让iOS开发者轻而易举地在iOS设备屏幕上显示PDF文件。
* [CLImageEditor](https://github.com/yackle/CLImageEditor) - 超强的图片编辑库，快速帮你实现旋转，防缩，滤镜等等一系列麻烦的事情。。
 



========
#### 视频音频处理
* [SCRecorder](https://github.com/rFlex/SCRecorder) - SCRecorder 短视频录制。
* [VideoPushDemo](https://github.com/pingguo-zangqilong/VideoPushDemo) - 视频剪辑 [视频特效制作1](http://www.jianshu.com/p/3006502912aa) [视频特效制作2](http://www.jianshu.com/p/6313025349a9)。
* [LLSimpleCamera](https://github.com/omergul123/LLSimpleCamera) - A simple, customizable camera control for iOS， 摄像头。
* [EZAudio](https://github.com/syedhali/EZAudio) - EZAudio 是一个 iOS 和 OSX 上简单易用的音频框架，[中文介绍](http://segmentfault.com/blog/news/1190000000370957),[官网](http://www.syedharisali.com/about)。


========
#### 测试及调试
* [HeapInspector](https://github.com/tapwork/HeapInspector-for-iOS) - HeapInspector是一个用于检测应用中的内存泄漏的开源调试工具。
* [Crashlytics](http://try.crashlytics.com/) - Crashlytics 崩溃报告 崩溃日志   [使用说明](http://www.infoq.com/cn/articles/crashlytics-crash-statistics-tools) 

========
#### 响应式框架
* [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) - ReactiveCocoa 受函数响应式编程激发。不同于使用可变的变量替换和就地修改，RAC提供Signals来捕获当前值和将来值（ [使用介绍](http://yulingtianxia.com/blog/2014/07/29/reactivecocoa/) ），[不错的例子](http://iiiyu.com/2014/12/26/learning-ios-notes-thirty-six/)。
* [BeeFramework](https://github.com/gavinkwoe/BeeFramework) -  与ReactiveCocoa类似，[BeeFramework用户指南 v1.0](http://www.lanrenios.com/tutorials/all/2012/1220/641.html)。
* [Objective-Chain](https://github.com/iMartinKiss/Objective-Chain) - Objective-Chain是一个面向对象的响应式框架，作者表示该框架吸收了 ReactiveCocoa 的思想，并且想做得更面向对象一些。

========
#### 消息推送
##### 客户端
* [SGPushDemo](https://github.com/sagiwei/SGPush/tree/master/SGPushDemo) - 消息推送客户端
* [Orbiter](https://github.com/mattt/Orbiter) - 消息推送客户端:Push Notification Registration for iOS.

##### 服务器端
 * [javapns源代码](https://code.google.com/p/javapns/downloads/list) - 消息推送的java服务端代码，注意：DeviceToken中间不能有空格。
 * [pushMeBaby](https://github.com/stefanhafeneger/PushMeBaby) - Mac端消息推送端代码，注意：DeviceToken中间要有空格。

========
#### 版本新API的Demo
* [iOS7-Sampler](https://github.com/shu223/iOS7-Sampler) - 整合了iOS7.0的一些十分有用的特性，比如：Dynamic Behaviors、碰撞检测、语音合成、视图切换、图像滤镜、三维地图、Sprite Kit（动画精灵）、Motion Effect（Parallax）、附近蓝牙或者wifi搜索连接、AirDrop、运动物体追踪（iPhone 5S以上，需要M7处理器）等等。对于日常的应用开发十分实用。 
* [iOS8-Sampler](https://github.com/shu223/iOS8-Sampler) - 日本的shuさん制作的 iOS8 参考代码集。01.Audio Effects ；02.New Image Filters；03.Custom Filters；04.Metal Basic；05.Metal Uniform Streaming；06.SceneKit；07.HealthKit；08.TouchID；09.Visual Effects；10.WebKit；11.UIAlertController；12.User Notification；13.Pedometer；14.AVKit；15.Histogram；16.Code Generator；17.New Fonts；18.Popover；19.Accordion Fold Transition

========
#### 代码安全
* [ios-class-guard](https://github.com/Polidea/ios-class-guard) - 一个用于混淆iOS的类名、方法名以及变量名的开源库。
* [《Protecting iOS Applications》](https://www.polidea.com/#!heartbeat/blog/Protecting_iOS_Applications)：文章系统地介绍了如何保护iOS程序的代码安全，防止反汇编分析。
* [fishhook](https://github.com/facebook/fishhook) - fishhook是Facebook开源的一个可以hook系统方法的工具。

========
#### Xcode插件
* 在Xcode启动的时候，Xcode将会寻找位于~/Library/Application Support/Developer/Shared/Xcode/Plug-ins文件夹中的后缀名为.xcplugin的bundle作为插件进行加载（运行其中的可执行文件）。[Xcode5 Plugins 开发简介](http://studentdeng.github.io/blog/2014/02/21/xcode-plugin-fun/)  [写个自己的Xcode4插件](http://joeyio.com/ios/2013/07/25/write_xcode4_plugin_of_your_own/)

* [Xcode 4 插件制作入门](http://www.onevcat.com/2013/02/xcode-plugin/) - Xcode 4 插件制作入门:Xcode所使用的所有库都包含在Xcode.app/Contents/的Frameworks，SharedFrameworks和OtherFrameworks三个文件夹下。其中和Xcode关系最为直接以及最为重要的是Frameworks中的IDEKit和IDEFoundation，以及SharedFrameworks中的DVTKit和DVTFoundation四个。
 
* [RTImageAssets](https://github.com/rickytan/RTImageAssets) - 一个 Xcode 插件，用来生成 @3x 的图片资源对应的 @2x 和 @1x 版本。

* [VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode) - 一个Xcode插件，build后，随手打开一个你之前的项目，然后在任意一个方法上面连按三下"/"键盘，就ok了。

* [java2Objective-c](https://github.com/google/j2objc) - Google公司出得java转Obje-C转换工具，转换逻辑，不转换UI。

* [RegX](https://github.com/kzaher/RegX) - 专治代码强迫症的 Xcode 插件，使用 Swift 和 Objective-C 编写。其用竖向对齐特定源代码的元素，使得代码更易读和易理解。[说明](http://www.cocoachina.com/ios/20141224/10743.html) ； 菜单：xcode——》Edit-》Regx 。

* [KSImageNamed](https://github.com/ksuther/KSImageNamed-Xcode) - 自动完成，特别是如果你正在写Objective-C，如果Xcode能自动完成文件名难道不会很伟大吗？比如图像文件的名称。

* [FuzzyAutocomplete](https://github.com/FuzzyAutocomplete/FuzzyAutocompletePlugin) - Xcode的实现自动完成还不完美，此插件能给出你所期望或想要的建议，设置：xcode-》Editor-》FuzzyAutocomplete-》plugin settings。

* [GitDiff](https://github.com/johnno1962/GitDiff) - Xcode的代码编辑器的一个微妙的补强，加上了足够的可见信息以了解上次git提交以来发生了什么变化，设置：xcode-》Edit-》GitDiff。

* [XToDo](https://github.com/trawor/XToDo) - 这个插件不仅凸显TODO，FIXME，???，以及！！！注释，也在便利列表呈现他们。 菜单：xcode-》view-》snippets;   调出列表显示: xcode-》view-》ToDo List ： ctrl + T 。 

* [Backlight](https://github.com/limejelly/Backlight-for-XCode) - 突出显示当前正在编辑的行。菜单：xcode-》view-》Backlight 。

* [CocoaPods](https://github.com/kattrali/cocoapods-xcode-plugin) - 该CocoaPods的插件增加了一个CocoaPods菜单到Xcode的产品菜单。如果你不喜欢命令行，那么你一定会喜欢这个插件。 [用CocoaPods做iOS程序的依赖管理 ]( 
http://tangqiaoboy.gitcafe.io/blog/2014/05/25/use-cocoapod-to-manage-ios-lib-dependency/)。

* [Peckham](https://github.com/markohlebar/Peckham) - 添加import语句比较麻烦，此插件 按Command-Control-P，给出的选项列表中选择要的头文件。先要安装[Alcatraz](http://alcatraz.io/) ,在终端输入： **curl -fsSL https://raw.github.com/supermarin/Alcatraz/master/Scripts/install.sh | sh** ； 重启xcode-》window-》Package Manager：搜索 **Peckham** 安装，打开Peckham.xcodeproj，编译 Peckham target，重启Xcode 。

* [Auto-Importer](https://github.com/lucholaf/Auto-Importer-for-Xcode) - Auto-Importer是一个自动导入类对应的头文件的Xcode插件。

* [Alcatraz](http://alcatraz.io/) -使用Alcatraz来管理Xcode插件 [使用说明](http://tangqiaoboy.gitcafe.io/blog/2014/03/05/use-alcatraz-to-manage-xcode-plugins/) 

========
#### 美工资源
* [TWG_Retina_Icons](https://github.com/markohlebar/Peckham) - 一套支持 Retina 高清屏的 iPhone 免费图标集。

#### 其他资源
* [githuber](http://githuber.info/#/index) - 最好用的GitHub人才搜索工具。   

========
#### 开发资源
##### 开发资料
* [Swift开源项目精选](https://github.com/ipader/SwiftGuide/blob/master/Featured.md) - Swift开源项目精选。
* [Swift中文指南](https://github.com/numbbbbb/the-swift-programming-language-in-chinese) - 中文版Apple官方Swift教程《The Swift Programming Language》，[老码版本](http://numbbbbb.gitbooks.io/-the-swift-programming-language-/content/)  [历史版本更新说明](http://numbbbbb.gitbooks.io/-the-swift-programming-language-/content/chapter1/03_revision_history.html)。
* [iOS-Core-Animation-Advanced-Techniques](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques) - 中文版iOS 高级动画技术。 
* [iOS开发的一些奇巧淫技1](http://www.jianshu.com/p/50b63a221f09) - TableView不显示没内容的Cell怎么办; 键盘事件：[IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager);  app不流畅:[KMCGeigerCounter](https://github.com/kconner/KMCGeigerCounter);  CoreData用起来好烦:[MagicRecord](https://github.com/magicalpanda/MagicalRecord);  CollectionView实现悬停的header:[CSStickyHeaderFlowLayout](https://github.com/jamztang/CSStickyHeaderFlowLayout)。
* [iOS开发的一些奇巧淫技2](http://www.jianshu.com/p/08f194e9904c) -  用一个pan手势来代替UISwipegesture的各个方向、拉伸图片、播放GIF、上拉刷新、把tableview里cell的小对勾的颜色改变、navigationbar弄成透明的而不是带模糊的效果、改变uitextfield placeholder的颜色和位置。
* [cocoapods安装指南](http://code4app.com/article/cocoapods-install-usage) - cocoapods安装指南。
* [RemoteControl](https://github.com/johnno1962/Remote) - Control your iPhone from inside Xcode for end-to-end testing 。
* [MVVM 介绍](http://objccn.io/issue-13-1/) - 替换MVC的开发模式。

 
##### 他人开源总结
* [code4app](http://www.code4app.com/) - 最多国人用的代码库。
* [cocoachina](http://code.cocoachina.com/) - 国内最热门的iOS社区的代码库。
* [awesome-ios](https://github.com/vsouza/awesome-ios) - 一个老外整理的。
* [Awesome Haskell资料大全](https://haskell.zeef.com/konstantin.skipor#block_28362_basics) -    Awesome Haskell 资料大全：框架，库和软件。
* [Cosmos](http://ios-cosmos.com) - The iOS Cosmos：收录了IOS绝大部分的开源框架和工具。
* [cocoacontrols](http://cocoacontrols.com) -  收集了很多UI控件效果代码，缺点是需要翻墙，而且代码分类不够好。
* [lexrus](https://github.com/lexrus) -  lexrus国内出名的iOS开源coder，非常库的label动画、textfield动画。

##### 中文开发博客列表
 * [唐巧整理](https://github.com/tangqiaoboy/iOSBlogCN) - 猿题库唐巧整理。

博客地址 | RSS地址
----- | -----
[OneV's Den](http://onevcat.com) | <http://onevcat.com/atom.xml>
[破船之家](http://beyondvincent.com) | <http://beyondvincent.com/atom.xml>
[NSHipster](http://nshipster.cn) | <http://nshipster.cn/feed.xml>
[Limboy 无网不剩](http://blog.leezhong.com/) | <http://feeds.feedburner.com/lzyy>
[唐巧的技术博客](http://blog.devtang.com) | <http://blog.devtang.com/atom.xml>
[Lex iOS notes](http://ios.lextang.com) | <http://ios.lextang.com/rss>
[念茜的博客](http://nianxi.net) | <http://nianxi.net/feed.xml>
[Xcode Dev](http://blog.xcodev.com) | <http://blog.xcodev.com/atom.xml>
[Ted's Homepage](http://wufawei.com/)| <http://wufawei.com/feed>
[txx's blog](http://blog.t-xx.me) | <http://blog.t-xx.me/atom.xml>
[KEVIN BLOG](http://imkevin.me) | <http://imkevin.me/rss>
[阿毛的蛋疼地](http://www.xiangwangfeng.com) | <http://www.xiangwangfeng.com/atom.xml>
[亚庆的 Blog](http://billwang1990.github.io) | <http://billwang1990.github.io/atom.xml>
[Nonomori](http://nonomori.farbox.com) | <http://nonomori.farbox.com/feed>
[言无不尽](http://tang3w.com) | <http://tang3w.com/atom.xml>
[Wonderffee's Blog](http://wonderffee.github.io) | <http://wonderffee.github.io/atom.xml>
[I'm TualatriX](http://imtx.me) | <http://imtx.me/feed/latest/>
[vclwei](http://vclwei.com) | <http://vclwei.com/posts.rss>
[Cocoabit](http://blog.cocoabit.com) | <http://blog.cocoabit.com/atom.xml>
[nixzhu on scriptogr.am](http://nixzhu.me) | <http://nixzhu.me/feed>
[不会开机的男孩](http://studentdeng.github.io) | <http://studentdeng.github.io/atom.xml>
[Nico](http://www.taofengping.com) | <http://www.taofengping.com/rss.xml>
[阿峰的技术窝窝](http://hufeng825.github.io) | <http://hufeng825.github.io/atom.xml>
[answer_huang](http://answerhuang.duapp.com) | <http://answerhuang.duapp.com/index.php/feed/>
[webfrogs](http://webfrogs.me) | <http://webfrogs.me/feed/>
[代码手工艺人](http://joeyio.com) | <http://joeyio.com/atom.xml>
[Lancy's Blog](http://gracelancy.com) | <http://gracelancy.com/atom.xml>
[I'm Allen](http://www.imallen.com) | <http://www.imallen.com/atom.xml>
[Travis' Blog](http://imi.im/)| <http://imi.im/feed>
[王中周的技术博客](http://wangzz.github.io/) |<http://wangzz.github.io/atom.xml>
[会写代码的猪](http://jiajun.org/)|<http://gaosboy.com/feed/atom/>
[克伟的博客](http://wangkewei.cnblogs.com/)|<http://feed.cnblogs.com/blog/u/23857/rss>
[摇滚诗人](http://cnblogs.com/biosli)|<http://feed.cnblogs.com/blog/u/35410/rss>
[Luke's Homepage](http://geeklu.com/) | <http://geeklu.com/feed/>
[萧宸宇](http://iiiyu.com/) | <http://iiiyu.com/atom.xml>
[Yuan博客](http://www.heyuan110.com/) | <http://www.heyuan110.com/?feed=rss2>
[Shining IO](http://shiningio.com/) | <http://shiningio.com/atom.xml>
[YIFEIYANG--易飞扬的博客](http://www.yifeiyang.net/) | <http://www.yifeiyang.net/feed>
[KooFrank's Blog](http://koofrank.com/) | <http://koofrank.com/rss>
[hello it works](http://helloitworks.com) | <http://helloitworks.com/feed>
[码农人生](http://msching.github.io/) | <http://msching.github.io/atom.xml>
[玉令天下的Blog](http://yulingtianxia.com) | <http://yulingtianxia.com/atom.xml>
[不掏蜂窝的熊](http://www.hotobear.com/) | <http://www.hotobear.com/?feed=rss2>
[猫·仁波切](https://andelf.github.io/) | <https://andelf.github.io/atom.xml>
[煲仔饭](http://ivoryxiong.org/) | <http://ivoryxiong.org/feed.xml>
[里脊串的开发随笔](http://adad184.com) | <http://adad184.com/atom.xml>
