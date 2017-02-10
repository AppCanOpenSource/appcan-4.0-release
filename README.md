# appcan-4.0-release

### 2017-02-10版本更新记录

版本号:iOS_Engine_4.1.0_170209_19

更新内容:  重构侧滑关闭组件;重构引擎动画;支持WidgetSDK

#### iOS插件：

1. 版本号: uexBaiduMap-iOS-4.0.3

   更新内容: 修复窗口关闭导致后续的搜索功能异常的问题

2. 版本号: uexChart-iOS-4.1.0

   更新内容: 支持4.1引擎

#### Android引擎：

1. 版本号: android_Engine_4.1.1_170110_01_system

   更新内容: X5内核修复，推送相关bug修复

2. 版本号: android_Engine_4.1.1_170110_01_x5

   更新内容: X5内核修复，推送相关bug修复

3. 版本号: android_Engine_4.1.1_170110_01_crosswork

   更新内容: X5内核修复，推送相关bug修复
   
#### Android插件：

1. 版本号: uexTencentLVB-android-4.0.2

   更新内容: 去除多余图片


### 2017-01-22版本更新记录

版本号:iOS_Engine_4.0.6_170122_01_Xcode8.1

更新内容:  修复解析相对路径URL时没有正确移除query和fragment的问题

#### iOS插件：

1. 版本号: uexAudio--iOS-4.0.1

   更新内容: 修复音效池接口内存泄露问题

2. 版本号: uexChatKeyboard-iOS-4.0.1

   更新内容: 添加getText，setText接口

3. 版本号: uexWeiXin-iOS-4.0.2

   更新内容: 修改全部function回调数据类型为对象

#### Android插件：

1. 版本号: uexWeiXin-android-4.0.3

   更新内容: 修改全部function回调数据类型为对象

2. 版本号: uexEasemob-android-4.1.1

   更新内容: 修复跨页面调用接口出错的问题

3. 版本号: uexChatKeyboard-android-4.0.1

   更新内容: 添加getText，setText接口 

4. 版本号: uexDownloaderMgr-android-4.1.4

   更新内容: （需要引擎4.1.0以上）修复某些url不能下载的问题


### 2017-01-10版本更新记录

#### iOS引擎：

版本号:iOS_Engine_4.0.5_170109_01_Xcode8.1

更新内容:  uexWindow.statusBarNotification接口重构

#### iOS插件：

1. 版本号: uexEasemob-iOS-4.0.1

   更新内容: SDK升级,支持ATS

2. 版本号: uexDownloaderMgr-iOS-4.0.1

   更新内容: 修复一个会导致崩溃的问题

3. 版本号: uexScanner-iOS-4.0.1

   更新内容: 修复首次启动用户确认相机权限时可能闪退的问题

#### Android引擎：

1. 版本号: android_Engine_4.1.1_170110_01_system

   更新内容: IDE支持显示console.log();actionSheet优化;修复推送问题

2. 版本号: android_Engine_4.1.1_170110_01_x5

   更新内容: IDE支持显示console.log();actionSheet优化;修复推送问题

3. 版本号: android_Engine_4.1.1_170110_01_crosswork

   更新内容: IDE支持显示console.log();actionSheet优化;修复推送问题
   
   
#### Android插件：

1. 版本号: uexAliPay-android-4.0.2

   更新内容: 修复支付成功之后没有回调的问题

2. 版本号: uexDevice-android-4.0.2

   更新内容: 增加网络状态监听的功能

3. 版本号: uexDownloaderMgr-android-4.1.3

   更新内容: 修复服务器返回2XX（非200、206）导致下载失败的问题，并修改自动处理重定向 

4. 版本号: uexLocation-android-4.0.2

   更新内容: 提高定位服务的存活率

5. 版本号: uexSecurityKeyboard-android-4.0.1

   更新内容: 增加自定义输入框样式、随机展示数字键盘等功能

6. 版本号: uexUploaderMgr-android-4.0.3

   更新内容: 修复服务器返回2XX（非200）导致上传失败的问题，并修改自动处理重定向 

7. 版本号: uexEasemob-android-4.1.0

   更新内容: (依赖引擎4.1)更新SDK，修复若干bug


### 2016-12-30版本更新记录

#### iOS插件：

1. 版本号: uexGaodeMap-iOS-4.0.2

   更新内容: SDK升级 支持ATS;新增resize接口;新增路径规划相关接口

2. 版本号: uexCamera-iOS-4.0.1

   更新内容: open接口修改为不对图片尺寸进行压缩

3. 版本号: uexGaodeNavi-iOS-4.0.1

   更新内容: SDK更新 支持ATS
      
#### Android插件：

1. 版本号: uexGaodeMap-android-4.0.2

   更新内容: 升级Sdk,支持路径规划

2. 版本号: uexGaoNavi-android-4.0.2

   更新内容: 升级Sdk

3. 版本号: uexImage-android-4.0.6

   更新内容: 裁剪支持不传src参数 

4. 版本号: uexTencentLVB-android-4.0.1

   更新内容: 添加录音权限

### 2016-12-23版本更新记录

#### iOS引擎：

版本号:iOS_Engine_4.0.4_161220_01_Xcode8.1

更新内容:  修正uexWindow.prompt回调参数异常的问题;uexWindow加载网页时,不再移除URL中的query和fragment;UEX_PARAM_GUARD系列宏,在发生参数异常时输出的日志等级从debug变为error

#### iOS插件：

1. 版本号: uexAliPay-iOS-4.0.1

   更新内容: SDK更新,添加新接口以支持新版"app接口支付"

2. 版本号: uexUnionPay-iOS-4.0.1

   更新内容: SDK更新,支持银联钱包支付,支持ATS

3. 版本号: uexBaiduMap-iOS-4.0.2

   更新内容: SDK更新,支持ATS;反地理编码现在可以返回更详细的信息

4. 版本号: uexImage-iOS-4.0.2

   更新内容: 优化加载网络图片的进度条; 回调修正,和文档保持一致

5. 版本号: uexMobSMS-iOS-4.0.1

   更新内容: SDK更新,支持ATS

6. 版本号: uexNIM-iOS-4.0.1

   更新内容: SDK更新,支持ATS

7. 版本号: uexQQ-iOS-4.0.1

   更新内容: SDK更新,支持ATS

8. 版本号: uexUmeng-iOS-4.0.1

   更新内容: SDK更新,支持ATS
      
#### Android插件：

1. 版本号: uexGestureUnlock-android-4.0.2

   更新内容: 手势密码界面调整

2. 版本号: uexScanner-android-4.0.3

   更新内容: 修复扫描返回json时，网页无法解析的问题

3. 版本号: uexBaiduMap-android-4.0.3

   更新内容: reverseGeocode返回详细信息 

4. 版本号: uexUploaderMgr-android-4.0.2

   更新内容: 修复文件名有汉字时出错的问题

5. 版本号: uexLocation-android-4.0.1

   更新内容: 更换AppKey

6. 版本号: uexAliPay-android-4.0.1

   更新内容: 支持支付宝新版接口

7. 版本号: uexCamera-android-4.0.1

   更新内容: 修复open和openInternal接口兼容3.0回调问题

### 2016-12-20版本更新记录

#### iOS插件：

1. 版本号: uexWeiXin-iOS-4.0.1

   更新内容: SDK升级至1.7.5 支持ATS

2. 版本号: uexImage-iOS-4.0.1

   更新内容: 支持4x3及16x9矩形裁剪

3. 版本号: uexFileMgr-iOS-4.0.3

   更新内容: 修复导致iCache模块异常的兼容性问题
   
#### Android插件：

1. 版本号: uexMiPush-android-4.0.0

   更新内容: 小米推送4.0插件

2. 版本号: uexActionSheet-android-4.0.1

   更新内容: 解决编译错误问题

3. 版本号: uexDataBaseMgr-android-4.1.0

   更新内容: (依赖引擎4.1.0)支持显示sql执行错误信息到IDE

4. 版本号: uexJpush-android-4.0.1

   更新内容: 修复onReceiveNotificationOpen回调两次的问题

5. 版本号: uexUploaderMgr-android-4.0.1

   更新内容: 修复uploadFile压缩参数失效的问题

### 2016-12-16版本更新记录

#### iOS插件：

1. 版本号: uexVideo-iOS-4.0.1

   更新内容: 修改视频播放画面显示不全、竖屏跳转横屏会卡在原位置

2. 版本号: uexActionSheet-iOS-4.0.1

   更新内容: 优化参数获取, 提高对3.x版本不规范参数的兼容性

3. 版本号: uexFileMgr-iOS-4.0.2

   更新内容: 修正部分cb接口回调参数与3.x版本不一致的问题

4. 版本号: uexJPush-iOS-4.0.1

   更新内容: 升级SDK；修正在iOS10+系统上extras参数与文档不一致的问题

#### Android引擎：

1. 版本号: android_Engine_4.1.0_161216_01_system

   更新内容: 支持IDE显示console.log()

2. 版本号: android_Engine_4.1.0_161216_01_x5

   更新内容: 支持IDE显示console.log()

3. 版本号: android_Engine_4.1.0_161216_01_crosswork

   更新内容: 支持IDE显示console.log()
   
#### Android插件：

1. 版本号: uexXmlHttpMgr-android-4.0.1

   更新内容: 修复cookie 的问题

2. 版本号: uexMobSMS-android-4.0.1

   更新内容: 删除敏感权限

3. 版本号: uexImage-android-4.0.5

   更新内容: (依赖引擎4.0.1)图片自动滚动到最新

4. 版本号: uexContact-android-4.0.1

   更新内容: 解决获取联系人号码重复的问题

5. 版本号: uexLog-android-4.0.1

   更新内容: 解决Log发送失败和Log发送的时序问题

### 2016-12-10版本更新记录

#### iOS引擎：

版本号:iOS_Engine_4.0.3_161208_01_Xcode8.1

更新内容:  添加接口uexWindow.setInlineMediaPlaybackEnable();新增窗口黑名单,修复uexEMM4.0报错的问题；推送上报逻辑更新,移除多余的Log；openPopover现在默认不会超出屏幕范围。

#### iOS插件：

1. 版本号: uexDataBaseMgr-iOS-4.0.1

   更新内容: 支持读取APP预置数据库

2. 版本号: uexDevice-iOS-4.0.1

   更新内容: 添加接口getIP(),可以获取本地IP地址

#### Android插件：

1. 版本号: uexDataBaseMgr-android-4.0.1

   更新内容: 支持读取APP预置数据库

2. 版本号: uexDevice-android-4.0.1

   更新内容: 添加接口getIP(),可以获取本地IP地址

3. 版本号: uexDownloaderMgr-android-4.0.1

   更新内容: 解决回调过快导致卡死的问题.

4. 版本号: uexWheelPickView-android-4.0.1

   更新内容: 解决3级分类不能显示全的bug。

### 2016-12-01版本更新记录

#### iOS插件：

1. 版本号: uexWebSocket-iOS-4.0.0

   更新内容: WebSocket插件出新

2. 版本号: uexMQTT-iOS-4.0.0

   更新内容: Mqtt插件出新

### Android引擎:

1. 版本号: android_Engine_4.0.1_161201_01_system

   更新内容: 显示图片支持自定义options，辅助uexImage插件修复ImageLoader未配置导致的crash问题。

2. 版本号: android_Engine_4.0.1_161201_01_x5

   更新内容: 显示图片支持自定义options，辅助uexImage插件修复ImageLoader未配置导致的crash问题。

3. 版本号: android_Engine_4.0.1_161201_01_crosswork

   更新内容: 显示图片支持自定义options，辅助uexImage插件修复ImageLoader未配置导致的crash问题。

#### Android插件：

1. 版本号: uexWebSocket-android-4.0.0

   更新内容: WebSocket插件出新

2. 版本号: uexMQTT-android-4.0.0

   更新内容: Mqtt插件出新

3. 版本号: uexBaiduMap-android-4.0.2

   更新内容: 修复open中心点失效的问题,searchRoutePlan支持function传入.

4. 版本号: uexImage-android-4.0.4

   更新内容: 引入ACEImageLoader解决ImageLoader未配置导致的crash问题，依赖引擎4.0.1版本。

### 2016-11-29版本更新记录

#### iOS插件：

1. 版本号: uexBackground-iOS-4.0.1

   更新内容: addTimer支持传入function


#### Android插件：

1. 版本号: uexGestureUnlock-android-4.0.1

   更新内容: 修复create接口第一个参数传空时崩溃的问题

2. 版本号: uexAudio-android-4.0.1

   更新内容: 修复play参数传-1不循环播放的问题

3. 版本号: uexImage-android-4.0.3

   更新内容: 修复usePng 为true时 不能保存图片的bug

4. 版本号: uexWeiXin-android-4.0.1

   更新内容: shareLinkContent支持网络图片

### 2016-11-25版本更新记录

### iOS引擎:

版本号: iOS_Engine_4.0.2_161125_01_Xcode8.1_Swift

更新内容: 修复网页reload时插件的JS上下文可能不会重置的bug,AppCanKit 完善JSArgument自定义运算符<~的注释

#### iOS插件：

1. 版本号: uexBaiduMap-iOS-4.0.1

   更新内容: 修复getCurrentLocation回调参数错误的问题

2. 版本号: uexGaodeMap-iOS-4.0.1

   更新内容: 新增接口addMultiInfoWindow

3. 版本号: uexFileMgr-iOS-4.0.1

   更新内容: 修正getFileHashValue接口在读取大文件的sha-1时可能会内存溢出的问题

4. 版本号: uexChart-iOS-4.0.1

   更新内容: 更新依赖引擎库,拓展 <~ 对UIColor的支持

5. 版本号: uexTouchID-iOS-4.0.1

   更新内容: canAuthenticate接口支持配置指纹验证模式

#### Android插件：

1. 版本号: uexGaodeMap-android-4.0.1      

   更新内容: 新增接口addMultiInfoWindow

2. 版本号: uexImage-android-4.0.2

   更新内容: 图片按时间顺序排列,修复图片选取状态错误的bug,支持矩形任意区域裁剪

### 2016-11-18版本更新记录

#### iOS插件：

1. 版本号: uexTencentLVB-iOS-4.0.0

   更新内容: 腾讯直播云插件出新

2. 版本号: uexTabIndicatorView-iOS-4.0.0

   更新内容: 导航栏插件出新

3. 版本号: uexImageFilter-iOS-4.0.0

   更新内容: 图片滤镜插件出新

#### Android插件：

1. 版本号: uexQQ-android-4.0.0      

   更新内容: 添加info信息

2. 版本号: uexNIM-android-4.0.0

   更新内容: allRecentSession接口新增sessionId属性

3. 版本号: uexTencentLVB-android-4.0.0

   更新内容: 腾讯直播云插件出新

4. 版本号: uexTabIndicatorView-android-4.0.0

   更新内容: 导航栏插件出新

5. 版本号: uexImageFilter-android-4.0.0

   更新内容: 图片滤镜插件出新
