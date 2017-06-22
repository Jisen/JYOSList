# GitHub第三方资源库整理(OC篇)

【[网络](#网络) &bull; [综合](#综合) &bull; [动画](#动画) &bull; [自动布局](#自动布局) &bull; [键盘交互管理](#键盘交互管理) &bull; [加载指示、HUD](#加载指示、HUD) &bull; [数据处理](#数据处理) &bull; [Categories](#Categories) &bull; [UIKit](#UIKit)  &bull; [Image](#Image) &bull; [Camera、视频](#Camera、视频) &bull; [瀑布流](#瀑布流) &bull; [Objective-C与JS交互](#Objective-C与JS交互) &bull; [工具、Xcode插件](#工具、Xcode插件) &bull; [测试](#测试) &bull; [资料](#资料) &bull; [其他](#其他)】

## 网络

- [AFNetworking](https://github.com/AFNetworking/AFNetworking):mattt大神的网络事件处理框架。
- [XMPPFramework](https://github.com/robbiehanson/XMPPFramework):`XMPP`,主要用于即时通讯。
- [CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket):异步`socket`请求框架。
- [Reachability](https://github.com/tonymillion/Reachability):用来检查应用当前的网络连接状况，是苹果Reachability类的直接替代品，支持ARC，支持block，使用GCD方法来通知网络接口的变化。
- [SocketRocket](https://github.com/square/SocketRocket):WebSocket协议是一种网络协议，它的Web设计实现了浏览器与服务器的双向通讯。通过使用WebSockets，你可以重复使用现有的工具建立网页，就像大多数移动应用程序重复使用他们API中的HTTP协议一样。
- [CocoaSPDY](https://github.com/twitter/CocoaSPDY):`Twitter出品`的一款关于`HTTP`请求的框架。
- [OHHTTPStubs](https://github.com/AliSoftware/OHHTTPStubs):测试篡改你app的`网络数据`、`响应时间`、`响应代码`、`和头文件`,非常容易就摧毁你的网络请求。

## 综合

- [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa):简称RAC,函数响应式编程框架。
- [YYKit](https://github.com/ibireme/YYKit):[ibireme](http://blog.ibireme.com)写的一款综合框架，包含[YYModel](https://github.com/ibireme/YYModel)、[YYCache](https://github.com/ibireme/YYCache)、[YYImage](https://github.com/ibireme/YYImage)、[YYWebImage](https://github.com/ibireme/YYWebImage)、[YYText](https://github.com/ibireme/YYText)、[YYKeyboardManager](https://github.com/ibireme/YYKeyboardManager)、[YYDispatchQueuePool](https://github.com/ibireme/YYDispatchQueuePool)、[YYAsyncLayer](https://github.com/ibireme/YYAsyncLayer)、[YYCategories](https://github.com/ibireme/YYCategories)。
- [AsyncDisplayKit](https://github.com/facebook/AsyncDisplayKit):`facebook出品`，被应用于`Paper`，是一款能够保持界面流畅性的iOS开源框架,即使是最复杂的用户界面,也可以让其流畅运行并快速响应。
- [RestKit](https://github.com/RestKit/RestKit):旨在与RESTful web服务的交互变得更简单快速,具有强大的特性：

    - 简单高层次的HTTP请求/响应系统；
    - 框架支持切换服务器以及环境；
    - Core Data支持；
    - 对象映射系统；
    - 生成数据库文件；
    - 可插入解析层。

- [NewsBlur](https://github.com/samuelclay/NewsBlur):是一个个人的新闻阅读器,将人们聚在一起谈论世界。

## 动画
### 动画引擎

- [POP](https://github.com/facebook/pop):`facebook出品`，动画引擎（推荐）。
- [Canvas](https://github.com/CanvasPod/Canvas):动画引擎，最喜欢的就是它关联`Runtime Attribute`了，可以在SB添加`KeyPath`直接加动画。
- [JazzHands](https://github.com/IFTTT/JazzHands):作用于`UIKit`的`keyframe-based`动画框架，具有良好的表现。
 
### 动画引擎使用

- [Popping](https://github.com/schneiderandre/popping)：使用pop动画引擎做的动画合集。
- [AGGeometryKit-POP](https://github.com/hfossli/AGGeometryKit-POP)：结合Pop的一个动画框架，带有力学动画效果。
- [FastAnimationWithPOP](https://github.com/WilliamZang/FastAnimationWithPOP):SB快速导入动画，以前用过的，不过推荐使用[Canvas](https://github.com/CanvasPod/Canvas)。
 
### 转场动画

- [VCTransitionsLibrary](https://github.com/ColinEberhardt/VCTransitionsLibrary):控制器之间的转场动画。
- [FDFullscreenPopGesture](https://github.com/forkingdog/FDFullscreenPopGesture):全屏`POP`的手势动画。
- [VVBlurPresentation](https://github.com/onevcat/VVBlurPresentation):王巍写的一款简单过渡到另外一个控制器，但是保持原来控制器的视图并模糊化，这对于一些提示比较有用。
- [LNPopupController](https://github.com/LeoNatan/LNPopupController):弹窗效果`present`到另外一个控制器，就像`Apple Music`app和`Podcasts`app里的效果一样。
- [KMNavigationBarTransition](https://github.com/MoZhouqi/KMNavigationBarTransition):不需要写任何代码就可实现对不同风格导航的转场动画管理。
- [AnimatedTransitionGallery](https://github.com/shu223/AnimatedTransitionGallery):许多种不同的转场动画风格。

### 其他动画

- [RGCardViewLayout](https://github.com/terminatorover/RGCardViewLayout):`City Guide App`的卡片滑动动画效果。
- [iCarousel](https://github.com/nicklockwood/iCarousel):卡片样式的旋转木马动画效果。
- [BCGenieEffect](https://github.com/Ciechan/BCGenieEffect):实现了在Mac OS 中最小化或最大化窗口时的过渡效果。

## 自动布局

- [Masonry](https://github.com/SnapKit/Masonry):自动布局，目前在用（推荐）。
- [PureLayout](https://github.com/PureLayout/PureLayout)：自动布局，`OC`、`Swift`皆可用。
- [SDAutoLayout](https://github.com/gsdios/SDAutoLayout):自动布局代码精简化，支持`Cell`和`TableView`高度自适应。
- [OAStackView](https://github.com/oarrabi/OAStackView):`UIStackView` iOS9之后的控件，对于自动布局这块非常方便，`OAStackView`就是兼容iOS7+系统的框架。
- [FDStackView](https://github.com/forkingdog/FDStackView):`百度知道团队出品`，兼容UIStackView iOS6+系统，[FDStackView Part1](http://blog.wtlucky.com/blog/2015/10/09/fdstackview-downward-compatible-uistackview-part-1/)、[FDStackView Part2](http://blog.wtlucky.com/blog/2016/01/19/fdstackview-downward-compatible-uistackview-part-2/)、[FDStackView Part3](http://blog.wtlucky.com/blog/2016/02/04/fdstackview-downward-compatible-uistackview-part-3/)这三篇文章是作者分析`FDStackView`的设计实现过程（推荐）。

## 键盘交互管理

- [YYKeyboardManager](https://github.com/ibireme/YYKeyboardManager):[YYKit](https://github.com/ibireme/YYKit)的组成部分，针对键盘管理（推荐）。
- [TPKeyboardAvoiding](https://github.com/michaeltyson/TPKeyboardAvoiding)：键盘交互事件。
- [IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager):键盘交互管理。

## 加载指示、HUD

- [MBProgressHUD](https://github.com/jdg/MBProgressHUD):加载进程指示框架，都知道。
- [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD):轻量的`HUD`。
- [NJKWebViewProgress](https://github.com/ninjinkun/NJKWebViewProgress):显示`webView`交互进程的控件。
- [Shimmer](https://github.com/facebook/Shimmer):facebook出品，给APP的任何view添加`shimmering`动画效果,这个框架最初就是作为Paper加载动画的。
- [PQFCustomLoaders](https://github.com/poolqf/PQFCustomLoaders):很有趣的自定义加载器。
- [DGActivityIndicatorView](https://github.com/gontovnik/DGActivityIndicatorView):很nice的加载指示器，有32种不要的加载指示风格。

## 数据处理
### 数据库

- [realm-cocoa](https://github.com/realm/realm-cocoa):`Realm`是Core Data和SQLite的代替品，操作移动数据库更加直接、快捷、耐用。
- [MagicalRecord](https://github.com/magicalpanda/MagicalRecord):对于使用`Core Data`做了非常好的封装，用`Core Data`值得一试。
- [fmdb](https://github.com/ccgus/fmdb):对`SQLite`进行了封装。

### 存储

- [YTKKeyValueStore](https://github.com/yuantiku/YTKKeyValueStore):唐巧写的Key-Value方式存储数据。
- [UICKeyChainStore](https://github.com/kishikawakatsumi/UICKeyChainStore):对`Keychain`的封装，让你使用`Keychain APIs`像`NSUserDefaults`一样简单。

### 转换

- [MJExtension](https://github.com/CoderMJLee/MJExtension):李明杰写的一款`JSON`转`Model`的框架。
- [Mantle](https://github.com/Mantle/Mantle):一款model层的框架，[为什么唱吧iOS 6.0选择了Mantle](http://www.iwangke.me/2014/10/13/Why-Changba-iOS-choose-Mantle/)。
- [JSONModel](https://github.com/icanzilb/JSONModel):一个解析服务器返回的Json数据,然后快速创建JSON 数据模型。同`Mantle`类似，不过`JSONModel`使用较为简单，但`Mantle`似乎更为强大，看个人选择。
- [Underscore.m](https://github.com/robb/Underscore.m):一个小型实用工具库，可以帮助开发者更方便地处理Objective-C中常见的数据结构

### 解析

- [JSONKit](https://github.com/johnezang/JSONKit):主要用于`JSON`数据处理解析。
- [Ono](https://github.com/mattt/Ono):mattt大神写的一款关于处理`XML`、`HTML`的框
架。
- [hpple](https://github.com/topfunky/hpple):解析XML/HTML的框架。

## Categories

- [iOS-Categories](https://github.com/shaojiankui/iOS-Categories):非常有用的Objective-C Categories,涉及到`Foundation`、`UIKit`、`CoreData`、`QuartCore`、`CoreLocation`、`MapKit`等。
- [octave](https://github.com/scopegate/octave):UI 操作音效，`UIControl`的category。
- [LTNavigationBar](https://github.com/ltebean/LTNavigationBar)：动态改变`UINavigationBar`的显示状态，类似手机QQ中QQ空间的导航效果。
- [FlatUIKit](https://github.com/Grouper/FlatUIKit):扁平化的UI视图集合。

## UIKit
### UI视图

- [JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController):一款优雅的关于聊天信息的UI框架。
- [SDCycleScrollView](https://github.com/gsdios/SDCycleScrollView):无限循环图片轮播器。
- [CoreLock](https://github.com/CharlinFeng/CoreLock):高仿支付宝手势密码。

### 日历视图

- [JTCalendar](https://github.com/jonathantribouharet/JTCalendar):自定义的日历视图。
- [GLCalendarView](https://github.com/Glow-Inc/GLCalendarView):同上，一款日历视图。

### 图表、绘图

- [PNChart](https://github.com/kevinzhow/PNChart):`周凯文`写的一款很好的图表框架。
- [core-plot](https://github.com/core-plot/core-plot):也是一款2D的绘图框架。

### 引导页、状态页

- [Onboard](https://github.com/mamaral/Onboard):只需少量代码就可创建非常nice的引导页。
- [DZNEmptyDataSet](https://github.com/dzenbot/DZNEmptyDataSet):没有请求到网络数据或者请求失败的视图展示，就好像`web`的404页面一样。

### View

- [CRPixellatedView](https://github.com/chroman/CRPixellatedView):UIView的子类，做像素化的动画处理。
- [SwipeView](https://github.com/nicklockwood/SwipeView):水平分页滑动视图。

### Alert、Sheet

- [MMPopupView](https://github.com/adad184/MMPopupView):高度可定制的alert、sheet。
- [TSMessages](https://github.com/KrauseFx/TSMessages):提示信息、通知信息控件。
- [RKDropdownAlert](https://github.com/cwRichardKim/RKDropdownAlert):基于facebook的app `Slingshot `的alert，灵感取自于`SVProgressHUD`的一个提示框架。
- [SCLAlertView](https://github.com/dogo/SCLAlertView):具有非常赞的动画的`Alert View`。
- [CMPopTipView](https://github.com/chrismiles/CMPopTipView):是一个开源的泡泡风格文本提示框控件。

### TableView

- [FXForms](https://github.com/nicklockwood/FXForms):非常容易创建table数据形式，用于设置页面非常理想。
- [VVeboTableViewDemo](https://github.com/johnil/VVeboTableViewDemo):VVebo剥离的TableView绘制,对`TableView`进行流畅度优化。
- [RETableViewManager](https://github.com/romaonthego/RETableViewManager):数据驱动`tableView`进行内容管理。

### TextView

- [SlackTextViewController](https://github.com/slackhq/SlackTextViewController):文本输入视图，对于消息编辑非常有用，类似于微信发送消息的那个输入框。

### Menu

- [RESideMenu](https://github.com/romaonthego/RESideMenu):左右侧视图视差效果`menu`,不过很久没有`commit`了。

- [AwesomeMenu](https://github.com/levey/AwesomeMenu):`Path2.0`里面的`menu`效果。

### Button

- [VBFPopFlatButton](https://github.com/victorBaro/VBFPopFlatButton):使用`pop`做的不同状态具有平缓过渡动画效果的扁平化button。
- [BEMCheckBox](https://github.com/Boris-Em/BEMCheckBox):一款可自定义的具有非常nice动画效果的`checkbox`。

### TextField

- [JVFloatLabeledTextField](https://github.com/jverdi/JVFloatLabeledTextField):编辑就会出现浮动的提示`label`，效果不错。

### Label

- [TTTAttributedLabel](https://github.com/TTTAttributedLabel/TTTAttributedLabel)
- [RQShineLabel](https://github.com/zipme/RQShineLabel):类似于`Secret`的文字闪烁动画。

### Font、Color

- [FontAwesomeKit](https://github.com/PrideChung/FontAwesomeKit):字体框架,支持`Font-Awesome`、`Foundation icons`、` Zocial`、`ionicons`。
- [Chameleon](https://github.com/ViccAlexander/Chameleon):类似颜色板一样，具有很多超赞的颜色可供直接使用。
- [Colours](https://github.com/bennyguitar/Colours):和`Chameleon`功能类似。
- [DKNightVersion](https://github.com/Draveness/DKNightVersion):对颜色的管理，融合了白天和黑夜的主题效果。

### Cell

- [SWTableViewCell](https://github.com/CEWendel/SWTableViewCell):滑动`Cell`的内容视图，出现功能按钮。（推荐）
- [MGSwipeTableCell](https://github.com/MortimerGoro/MGSwipeTableCell):功能同上。
- [UITableView-FDTemplateLayoutCell](https://github.com/forkingdog/UITableView-FDTemplateLayoutCell):`sunnyxx`写的，自动计算cell动态高度。

## CoreText、AttributeText

- [DTCoreText](https://github.com/Cocoanetics/DTCoreText):允许使用`HTML`代码的Core Text框架。
- [YYText](https://github.com/ibireme/YYText):非常强大的富文本显示和编辑框架。（推荐）

## Image

- [GPUImage](https://github.com/BradLarson/GPUImage):GPUImage 是iOS下一个开源的基于GPU的图像处理库,提供各种各样的图像处理滤镜,并且支持照相机和摄像机的实时滤镜。

### 图片加载、缓存

- [SDWebImage](https://github.com/rs/SDWebImage):异步图片下载处理，支持缓存，我相信大部分开发者都用过。
- [PINRemoteImage](https://github.com/pinterest/PINRemoteImage):对图片下载、加载、缓存的管理，线程安全且快速，对于网络图片具有很好的表现力。
- [Haneke](https://github.com/Haneke/Haneke):轻量的图片缓存框架。
- [AsyncImageView](https://github.com/nicklockwood/AsyncImageView):异步图片处理的一个简单Extension。
- [Concorde](https://github.com/contentful-labs/Concorde):下载和解码`JPEGs`格式图片。

### GIF

- [FLAnimatedImage](https://github.com/Flipboard/FLAnimatedImage):Gif引擎框架。
- [YLGIFImage](https://github.com/liyong03/YLGIFImage):异步Gif解码，播放Gif图片，占用内存少。

## Camera、视频

- [XCDYouTubeKit](https://github.com/0xced/XCDYouTubeKit):`YouTube`视频播放框架。
- [ZFPlayer](https://github.com/renzifeng/ZFPlayer):基于`AVPlayer`支持横屏、竖屏的视频播放器。
- [kxmovie](https://github.com/kolyvan/kxmovie):使用`ffmpeg`制作的一款视频播放器。
- [PBJVision](https://github.com/piemonte/PBJVision):一款`camera`的引擎，支持`录屏`、`慢动作`、`获取图片`等特性，且`camera`可自定义。
- [MWPhotoBrowser](https://github.com/mwaterfall/MWPhotoBrowser):一款优雅的图片、视频资源浏览器。

## 瀑布流

- [CHTCollectionViewWaterfallLayout](https://github.com/chiahsien/CHTCollectionViewWaterfallLayout):UICollectionView的瀑布流。
 
## Objective-C与JS交互

- [JSPatch](https://github.com/bang590/JSPatch):`JSPath`充当`Objective-C`与
`Javascript` 交互的桥梁。
- [WebViewJavascriptBridge](https://github.com/marcuswestin/WebViewJavascriptBridge):`Objective-C`与
`Javascript` 交互通信过程中，和`JSPath`一样充当桥梁。

## 地图、地理位置信息、LBS

- [LocationManager](https://github.com/intuit/LocationManager):非常容易获取设备当前地理位置信息的框架。
 
## ReactiveCocoa

- [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa):简称RAC。
- [MVVMReactiveCocoa](https://github.com/leichunfeng/MVVMReactiveCocoa):使用ReactiveCocoa结合MVVM模式做的一个Demo。
 
## Runtime

- [RuntimeBrowser](https://github.com/nst/RuntimeBrowser):有关运行时操作的工具，你有权使用运行时所有的类。 
- [iOS-Runtime-Headers](https://github.com/nst/iOS-Runtime-Headers):使用`RuntimeBrowser `导出的iOS`framework`的头文件。
 
## Block

- [BlocksKit](https://github.com/zwaldowski/BlocksKit) :对于使用`Block`来说更加方便、高效,不过好久没有`commit`了。
 
## KVO

- [KVOController](https://github.com/facebook/KVOController):`facebook出品`，它是一个简单安全的 KVO工具,构建了一个基于 Cocoa 的 time-tested key-value 监控实现，提供简单方便、线程安全的 API。
 
## AOP、Method Swizzling

- [Aspects](https://github.com/steipete/Aspects):一个简洁高效的用于使iOS支持AOP面向切面编程的库。
 
## 路由器、Deep Link

- [JLRoutes](https://github.com/joeldev/JLRoutes):引入路由器的概念`handle complex URL schemes`、`deep link`(推荐)。
- [DeepLinkKit](https://github.com/button/DeepLinkKit)、[routable-ios](https://github.com/clayallsopp/routable-ios)、[HHRouter](https://github.com/lightory/HHRouter):功能同上。

## 测试

- [Kiwi](https://github.com/kiwi-bdd/Kiwi):iOS的BDD框架。
- [specta](https://github.com/specta/specta):轻量的TDD/BDD测试框架。
- [KIF](https://github.com/kif-framework/KIF):全称是Keep It Functional,来自`Square`,是一款专为iOS设计的移动应用测试框架

## 日志

- [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack):是Mac和iOS上一个集快捷、简单、强大和灵活于一身的日志框架。

## 工具、Xcode插件
### 工具

- [Alcatraz](https://github.com/alcatraz/Alcatraz):Xcode插件管理神器，当然还有些其他的包管理功能。
- [FLEX](https://github.com/Flipboard/FLEX):一款很好的调试工具，同样是`Flipboard`出品。
- [PonyDebugger](https://github.com/square/PonyDebugger):原生app使用`Chrome`开发工具进行远程的网路和数据`debug`。
- [xctool](https://github.com/facebook/xctool):`facebook出品`的取代`Apple's xcodebuild `,让编译和测试更简单。
- [Tweaks](https://github.com/facebook/Tweaks):`facebook出品`的快速原型开发工具，能在应用上实时调整参数并测试效果。
- [EarlGrey](https://github.com/google/EarlGrey):`google出品`的UI自动测试工具。
- [GitUp](https://github.com/git-up/GitUp)：用于Git交互。

### 插件

- [injectionforxcode](https://github.com/johnno1962/injectionforxcode):运行中的程序，然后在Xcode中动态插入代码，你可以实时看到编译器中的变动。
- [CATweaker](https://github.com/keefo/CATweaker):创建`CAMediaTimingFunction `曲线的一个帮助工具，该插件可以实时观看你创建的曲线，而且可调整。
- [KSImageNamed-Xcode](https://github.com/ksuther/KSImageNamed-Xcode):自动`call` imageNamed：获取图片资源名字填充，且相应图片在左侧可见。
- [XAlign](https://github.com/qfish/XAlign):自动代码对齐插件。
- [VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode):`王巍`写的一款编写文本的插件，用于注释非常方便。
- [SCXcodeSwitchExpander](https://github.com/stefanceriu/SCXcodeSwitchExpander):自动填充`Switch`语句的枚举case值。
- [RTImageAssets](https://github.com/rickytan/RTImageAssets):给定一张`@3x`的图片，自动生成其他像素的图片，也可以给定一张`@2x`的图自动片生成`@3x`的图片。
- [ESJsonFormat-Xcode](https://github.com/EnjoySR/ESJsonFormat-Xcode):将JSON格式化输出为模型的属性插件。
- [FuzzyAutocompletePlugin](https://github.com/FuzzyAutocomplete/FuzzyAutocompletePlugin):代码索引、自动补全代码的插件。
- [ColorSense-for-Xcode](https://github.com/omz/ColorSense-for-Xcode):主要针对RGB颜色值，可实时查看RGB颜色。

## API、SDK

- [facebook-ios-sdk](https://github.com/facebook/facebook-ios-sdk)：facebook的sdk，使用它可以集成facebook的一些API。
- [octokit.objc](https://github.com/octokit/octokit.objc):`GitHub`API。

## 其他

- [PKRevealController](https://github.com/pkluz/PKRevealController):是一个iOS平台上的视图控制器集合，通过展现多个视图控制器来进行控制器之间的切换,设置简单，高度灵活。
- [nimbus](https://github.com/jverkoey/nimbus):旨在落实Three20，但是提供文档放在第一位，其次才是功能。
- [Chameleon](https://github.com/BigZaphod/Chameleon):就像是一个港口，有`iPhone`、`iPad`、`Mac`几个分支，用于处理不同平台。
- [iOS-Artwork-Extractor](https://github.com/0xced/iOS-Artwork-Extractor):可以把所有图片和emoji符号提取出来，并导入png文件。
- [Bolts-ObjC](https://github.com/BoltsFramework/Bolts-ObjC):集成多任务处理的，和GCD、NSOperation的作用有点类似。

## 资料

- [iOSInterviewQuestions](https://github.com/ChenYilong/iOSInterviewQuestions):ios面试题集锦。
- [open-source-ios-apps](https://github.com/dkhamsing/open-source-ios-apps#apple-tv):关于iOS开发一些开源的资源集锦，涉及iOS开发的各个方面。
- [trip-to-iOS](https://github.com/Aufree/trip-to-iOS):iOS学习资料整理。



