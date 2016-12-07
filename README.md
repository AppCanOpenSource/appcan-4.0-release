# appcan-4.0-release

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

### 2016-12-07版本更新记录

#### iOS引擎：

版本号: iOS_Engine_4.0.3_161207_01_Xcode8.1

更新内容: 新增窗口黑名单,修复uexEMM4.0报错的问题；推送上报逻辑更新,移除多余的Log；openPopover现在默认不会超出屏幕范围。

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

3. 版本号: uexDownloadMgr-android-4.0.1

更新内容: 解决回调过快导致卡死的问题.

4. 版本号: uexWheelPickView-android-4.0.1

更新内容: 解决3级分类不能显示全的bug。