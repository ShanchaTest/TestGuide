# 程序员山茶-测试资料

<p>
<a href="https://sm.ms/image/gUXkOaj23IeY9ib" target="_blank"><img src="https://s2.loli.net/2023/12/23/gUXkOaj23IeY9ib.png" ></a>

</p>




软件测试各类资源清单，包括测试工具、测试框架、学习资源和测试网站。
- [测试学习与成长路线](#测试成长路线)
  - [测试基础](#测试基础)
  - [自动化测试](#自动化测试)
  - [web自动化](#web自动化)
  - [接口协议与抓包](#接口协议与抓包)
  - [接口测试](#接口测试)
  - [性能与负载测试](#性能与负载测试)
  - [容器与Docker技术](#容器与Docker技术)
  - [持续集成与持续交付](#持续集成与持续交付)
  - [测试平台与质量管理](#测试平台与质量管理)
  - [测试面试合集](#测试面试合集)
  - [面试官意图50例](#面试官意图50例)
  

- [测试工具](#测试工具)
  - [抓包工具](#抓包工具)
  - [接口工具](#接口工具)
  - [压力测试](#压力测试)
  - [Android测试工具](#Android测试工具)
  - [iOS测试工具](#iOS测试工具)
  - [Web测试工具](#Web测试工具)
  - [自动化工具](#自动化工具)
  - [IDE工具](#IDE工具)
  - [编译和反编译](#编译和反编译)
  - [终端](#终端)
  - [云测](#云测)
  - [数据库](#数据库)
  - [移动端性能](#移动端性能)
  - [监控/报表](#监控/报表)
  - [用例设计](#用例设计)
  - [测试环境](#测试环境)
  - [持续集成](#持续集成)
  - [项目管理](#项目管理)
  - [在线文档](#在线文档)
  - [版本控制](#版本控制)
  - [安全测试](#安全测试)
  - [代码扫描](#代码扫描)
- [测试框架](#测试框架)
  - [整站项目](#整站项目)
  - [前端模版](#前端模版)
  - [后端项目](#后端项目)
- [学习资源](#学习资源)
  - [视频资源](#视频资源)
  - [测试书籍](测试书籍)
  - [编程学习](#编程学习)
  - [面试相关](#面试相关)
- [测试网站](#测试网站)
  - [测试社区](#测试社区)

---
# 测试成长路线

## 测试基础
* [测试基础流程模型](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247493219&idx=1&sn=dd6ef48d46583512fcc62b2c25eecabb&chksm=fc6727ffcb10aee96201970486acd7e2453908d1f04078cf5d1e333137f316a27d5e7bfe25a0#rd) - 阐明测试概念、测试基本原则、测试流程
* [常见的测试模型](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247493223&idx=1&sn=906646916e11fd4d5d2200a37c406b3e&chksm=fc6727fbcb10aeed196d19483e664712fbcc61cf7ae9bec4b1b92fddc6668cd90399c46637ec#rd) - 测试模型，及其使用场景
* [测试技术体系](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247493430&idx=1&sn=4f1fa404ccf08d460929ee9da93f41a2&chksm=fc6726aacb10afbc2b4e4575b5aa9edbcd205b8ebcf176eb0b0b28ac4ce2a7599a37ad7b9fd2#rd) - 测试如何分类，以及测试体系有哪些种类及其组成内容
* [多维度测试平台/工具](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247493430&idx=1&sn=4f1fa404ccf08d460929ee9da93f41a2&chksm=fc6726aacb10afbc2b4e4575b5aa9edbcd205b8ebcf176eb0b0b28ac4ce2a7599a37ad7b9fd2#rd) - 测试人常用的测试平台及测试工具推荐
* [测试计划与测试方案](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247494045&idx=1&sn=16f1f803f504233e2a0dc9d721546c68&chksm=fc672801cb10a117de350f13e4d8b0fe698ceec004a91e8d91c220447ba1e356e664bc264279#rd) - 测试计划与测试方案
* [测试常用的 100 个shell指令](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247494045&idx=1&sn=16f1f803f504233e2a0dc9d721546c68&chksm=fc672801cb10a117de350f13e4d8b0fe698ceec004a91e8d91c220447ba1e356e664bc264279#rd) - 测试在软件测试过程中常用的shell指令
* [shell三剑客应用实例 - 日志分析](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247494176&idx=1&sn=15506522604cf1302aa35157f8c1e412&chksm=fc672bbccb10a2aa46748c91dafca78f552a592225e97365f7492d9aec726f46ba7c99769c1a#rd) - 使用shell三剑客对nginx日志进行分析处理
* [python基础语法入门](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247494208&idx=1&sn=d31dcc95385e12e9e2840b81b3b094e5&chksm=fc672bdccb10a2ca0997d774caf603e8e3d1b168576dcd9eb3501445a701099bd0322721ec63#rd) - 测试常用语言python语法入门
* [Java基础入门](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247494316&idx=1&sn=ade067f6c4b14491408e93ebd3e0e6f3&chksm=fc672b30cb10a2266d3ff7ae41bfe10a55de3e2b469e8a22dc719c964df9791280e6331a5812#rd) - 测试常用语言Java语法入门

## 自动化测试
* [为什么要做自动化测试](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247494417&idx=1&sn=25901f55ccd8e8dc8cb80beaf2ae66dd&chksm=fc672a8dcb10a39b061030fc8d533e9be3008a607fe929b5992c9a0ba484439b34bde7c210f0#rd) - 自动化测试的背景，及自动化测试会被应用在哪些项目中
* [unittest测试框架](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247494449&idx=1&sn=75dbab0b374474eed2dc42241c5d0064&chksm=fc672aadcb10a3bb9a2f6098f20303502e8bc49c642f3271a8871a9b0f2ba30fb81ac00b4acf#rd) - python自动化测试框架unittest的使用
* [unittest其他三种加载方式](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247494463&idx=1&sn=36fbb0e71a95a14738cbc047588ea813&chksm=fc672aa3cb10a3b50bbe0dae3644582df817318dbaa1ed1afb8a2e866e2089e606d5c3f7c8e5#rd) - unittest其他三种加载方式
* [定制unittest测试报告](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247494478&idx=1&sn=295f754ea0c5e00033687786fa29e882&chksm=fc672ad2cb10a3c4618b8575f5edb067dc2e0d71afcc0dbd81e5f78a4f82788f43540f765f00#rd) - unittest如何定制测试报告
* [pytest测试框架的基本使用](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247494802&idx=1&sn=b27c25a55b8dda3d779b7bb2835a83f5&chksm=fc672d0ecb10a418823c15eef494dc2da88f064f4439b478116742e0ec0327d51c8a60e52534#rd) - python + pytest测试框架的基本使用
* [pytest + allure定制报告](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247495037&idx=1&sn=60bd89ee2244cc92d500b429ea900ddb&chksm=fc672ce1cb10a5f75909883b9e279bc3d07bd98c677cfa834c14eccafac28724d975ad5e6760#rd) - pytest + allure如何定制测试报告
* [python数据驱动入门](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247495241&idx=1&sn=63aa515d5a8bcc06710a31be0c9eb446&chksm=fc672fd5cb10a6c3d83e6981b6f976e1cc3e523bb9ad8e5fa74ce16e12c142f8945beccf759d#rd) - 数据驱动入门

## web自动化
* [web自动化测试框架：Selenium简介](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247495565&idx=1&sn=77ea0a971946c0f64c4bf960606d0171&chksm=fc672e11cb10a707fd25dda112b699a4176dfe33400d6fed79d1ebd8e979f94b83776ee5b619#rd) - Selenium框架简介
* [使用selenum ide录制测试用例](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247495577&idx=1&sn=f9da8da28fe0861b71b00b2fcac1a6c4&chksm=fc672e05cb10a7135a928365e35df436c70bce82495c1976fce622c733bfef1c73c767b0a445#rd) - 使用Selenium录制第一个测试用例
* [持续更新ing]
* [持续更新ing]
* [持续更新ing]

## 接口协议与抓包
* [自动化测试价值](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247496090&idx=1&sn=377fbeb465a1f589aa19a2f228ec9ff8&chksm=fc673006cb10b910a0f67863cb847a37304b42426d4e91360f21fb846d4ba7fe146fdd9dc28f#rd) - 了解自动化测试的价值与背后意义
* [OSI模型与TCP/IP模型](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247496340&idx=1&sn=dd9285e51677c2a5b1207dbf382a077a&chksm=fc673308cb10ba1ec68b234325a3ce67562bf07793a26a736728867b9d33c1bd84d85bb1b6ba#rd) - OSI与TCP/IP网络协议模型,基础中的基础
* [持续更新ing]

## 接口测试
* [python + request接口测试入门](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247496077&idx=1&sn=8e26c182252eda69ac55f5e13b84c5bd&chksm=fc673011cb10b90718c06ce49baa0341eb3721e83b1ef42379bdd461e2feb57c10bcb39d2c23#rd) - python + request接口测试入门
* [持续更新ing]
* [持续更新ing]
* [持续更新ing]
  
## 性能与负载测试
* [持续更新ing]

## 容器与Docker技术
* [持续更新ing]

## 持续集成与持续交付
* [持续更新ing]


## 测试平台与质量管理
* [持续更新ing]


## 测试面试合集
* [那个拿了12个offer的人，自我介绍是这么写的](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247496124&idx=1&sn=d84fcb6fa6b529f0d351d0cb6a1e8836&chksm=fc673020cb10b936ffe0662d2d2550f282ae6d2a65ac5fd1a2d26aee2b33b2e84d894882b93a#rd) - 一个好的自我介绍，帮你提高10%的通过率


## 面试官意图50例
* [开始的 5 道题，50%决定你的去留](https://mp.weixin.qq.com/s?__biz=MzU2MjY5ODQ4Mw==&mid=2247495289&idx=1&sn=2bf7f6033a6de49aec949a597471ca3e&chksm=fc672fe5cb10a6f39dcc1f283fcfde17d996d7b8d0ddb6b2987611726b44c5844cce61aa880f#rd) - 
* [持续更新ing]
  
# 测试工具

## 抓包工具

*业内常用的抓包工具*

* [Charles](https://www.charlesproxy.com/) - 支持HTTP/HTTPS，支持Mock数据/弱网测试
* [Fiddler](https://www.telerik.com/fiddler) - 支持HTTP/HTTPS，支持Mock数据/弱网测试
* [Wireshark](https://www.wireshark.org/) - 网络封包分析软件，支持TCP、UDP等传输层协议抓包
* [mitmproxy](https://www.mitmproxy.org/) - 基于Python的网络抓包工具，支持HTTP/HTTPS，支持二次开发
* [anyproxy](https://github.com/alibaba/anyproxy) - 阿里巴巴开源，基于Node.js的网络抓包工具，支持HTTP/HTTPS，支持二次开发
* [Stream（iOS）](https://apps.apple.com/cn/app/stream/id1312141691) - iOS最好用的抓包工具，不用PC做代理
* [tcpdump](http://www.androidtcpdump.com/android-tcpdump/downloads) - 安卓抓包工具

## 接口工具

*业内常用的接口调试工具*

* [Postman](https://www.postman.com/) - 谷歌出品的优秀接口调试工具
* [Postwoman](https://github.com/hoppscotch/hoppscotch) - Postman开源替代品
* [Jmeter](https://jmeter.apache.org/) - Apache开源项目，适合压测/接口测试
* [Swagger](https://swagger.io/) - 丝袜哥，适配多种编程语言，接口文档和调试工具
* [Yapi](https://gitee.com/suxiaoxin123/yapi) - 接口管理平台，支持Mock数据，支持Postman/Swagger导入接口数据
* [requests](http://python-requests.org/) - python的HTTP请求库
* [grequests](https://github.com/spyoungtech/grequests) - requests + gevent for 异步 HTTP 请求库
* [aiohttp](https://github.com/aio-libs/aiohttp) - 基于python的asyncio的HTTP请求库

## 压测工具

*业内常用的压测工具*

* [Jmeter](https://jmeter.apache.org/) - Apache开源项目，适合压测/接口测试
* [Loadrunner](https://www.microfocus.com/en-us/products/performance-engineering/overview) - 老牌压测工具
* [Locust](https://www.locust.io/) - 开源的压测工具
* [go-stress-testing](https://github.com/link1st/go-stress-testing) - 基于Go语言开发的开源压测工具
* [ab](http://httpd.apache.org/) - ab是apache自带的压力测试工具
* [pts](https://www.aliyun.com/product/pts) - 阿里云的商业压测软件
* [wrk](https://github.com/wg/wrk) - C语言开源压测工具

## Android测试工具

*移动端测试工程师常用的 Android 测试工具*

- [adb](https://developer.android.com/studio/command-line/adb.html) - Android 调试桥，Android SDK自带的调试工具
- [Android Studio](https://developer.android.google.cn/studio/) - Android IDE工具，自带调试功能
- [aapt]() - Android 资源包管理工具，Android SDK自带的工具
- [Chrome Inspect](chrome://inspect/#devices) - Chrome浏览器调试 Android webview 的工具
- [uiautomatorviewer](https://android-sdk.en.softonic.com/mac) - Android 控件树定位工具，Android SDK自带

## iOS测试工具

*移动端测试工程师常用的 iOS 测试工具*

* [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice) - 与iOS设备进行通信的跨平台协议库
* [pymobiledevice](https://github.com/iOSForensics/pymobiledevice) - libimobiledevice的Python实现
* [imobiledevice](http://docs.quamotion.mobi/docs/imobiledevice/download/) - Quamotion提供的libimobiledevice的Windows平台可执行版本
* [XCode](https://developer.apple.com/xcode/) - iOS IDE工具，自带调试功能
* [XCTest](https://developer.apple.com/documentation/xctest) - iOS 单元测试工具
* [testflight](https://testflight.apple.com/) - iOS 灰度测试工具

## Web测试工具

*Web测试工程师常用的测试工具*

- [chrome](https://www.google.cn/chrome/) - 谷歌浏览器，F12 调试
- [firefox](http://www.firefox.com.cn/) - 火狐浏览器
- [IE](https://support.microsoft.com/zh-cn/help/17621/internet-explorer-downloads) - 远古时代的浏览器
- [Edge](https://www.microsoft.com/zh-cn/edge) - 微软出品的浏览器，IE的替代品
- [IETester](http://www.my-debugbar.com/wiki/IETester/HomePage) - 浏览器兼容性测试工具
- [Browsershots](http://browsershots.org/) - 在线的浏览器兼容性测试工具
- [在线工具](https://tool.lu/) - 实用在线小工具（json解析/时间戳/IP地址查询）

## 自动化工具

*常用的自动化测试底层框架（工具）*

- [Appium](http://appium.io/) - 最主流的 APP UI 自动化测试框架，可支持 Android/iOS
- [Selenium](http://www.selenium.org.cn/) - 最主流的 WEB UI 自动化测试框架
- [按键精灵](http://www.anjian.com/download.htm) - Windows 自动化工具
- [PyAutoGUI](https://muxuezi.github.io/posts/doc-pyautogui.html) - Python库，可以模拟鼠标键盘操作
- [uiautomator2](https://github.com/openatx/uiautomator2) - 基于 Python 的 UI 自动化测试框架，可支持 Android/iOS
- [wda](https://github.com/facebookarchive/WebDriverAgent) - facebook 开源的 iOS 自动化测试工具
- [ATX](https://github.com/NetEaseGame/ATX) - 基于图像识别完成游戏的自动化操作
- [Appetizer](https://www.appetizer.io/) - 移动开发智能化平台，集成多种移动端测试套件
- [Airtest](http://airtest.netease.com/) - 网易开源的游戏自动化测试工具
- [unittest](https://docs.python.org/3/library/unittest.html) - 基于 Python 的单元测试工具，常用于管理自动化测试用例
- [Pytest](https://learning-pytest.readthedocs.io/zh/latest/) - 基于 Python 的单元测试工具，常用于管理自动化测试用例
- [Junit](https://junit.org/junit5/) - 基于 Java 的单元测试工具，常用于管理自动化测试用例
- [TestNG](https://testng.org/doc/) - 基于 Java 的单元测试工具，常用于管理自动化测试用例
- [Allure](https://docs.qameta.io/allure/#_about) - 自动化报告生成框架（搭配 Pytest 使用）
- [HTMLTestRunnerCN](https://github.com/findyou/HTMLTestRunnerCN) - 自动化报告生成框架（搭配 unittest 使用）

## IDE工具

*常用的代码编写和调试工具*

- [IntelliJ IDEA](https://www.jetbrains.com/idea/) - Java 开发工具
- [PyCharm](https://www.jetbrains.com/pycharm/) - Python 开发工具
- [Jupyter Notebook](https://jupyter.org/install) - Python 算法/数据分析/可视化演示
- [PhpStorm](https://www.jetbrains.com/phpstorm/) - PHP（拍黄片） 开发工具
- [WebStorm](https://www.jetbrains.com/webstorm/) - 前端 开发工具
- [Goland](https://www.jetbrains.com/go/) - Go（够烂的） 开发工具
- [Android Studio](https://developer.android.google.cn/studio/) - Android 开发工具
- [XCode](https://developer.apple.com/xcode/) - iOS 开发工具
- [VSCode](https://code.visualstudio.com/) - 轻量级 开发工具
- [Visual Studio](https://visualstudio.microsoft.com/zh-hans/products/) - C/C++ 开发工具
- [Hbuider](https://www.dcloud.io/) - 轻量级 前端 开发工具
- [微信开发者工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html) - 微信小程序 开发工具
- [小程序开发者工具](https://render.alipay.com/p/f/fd-jwq8nu2a/pages/home/index.html) - 支付宝小程序 开发工具
- [sublime](http://www.sublimetext.com/) - 轻量级 开发工具

## 编译和反编译

*常用的代码编译和反编译工具*

- [Maven](https://maven.apache.org/) - Java 工程依赖管理和构建工具
- [Ant](http://ant.apache.org/) - Java 工程构建工具
- [Gradle](https://gradle.org/) - Java 工程依赖管理和构建工具
- [webpack](https://www.webpackjs.com/) - 前端资源加载/打包工具
- [npm](https://www.npmjs.com/) - Node.js包管理工具
- [gulp](https://www.gulpjs.com.cn/) - 前端 基于流的自动化构建工具
- [jd-gui](https://github.com/java-decompiler) - Java 反编译工具
- [ApkTool](http://ibotpeaches.github.io/Apktool/) - APK反编译工具
- [NET.Reflector](https://www.red-gate.com/products/dotnet-development/reflector/) - Unity安卓DLL代码文件反编译工具
- [AssetStudio](https://github.com/Perfare/AssetStudio) - Unity AssetBundle破解
- [dotPeek](http://www.jetbrains.com/decompiler/) - .NET 反编译工具

## 终端

*常用的终端连接工具*

- [Xshell](https://www.netsarang.com/zh/xshell/) - Windows 下好用的终端连接工具
- [SecureCRT](https://www.vandyke.com/download/securecrt/6.7/index.html) - Windows 下好用的终端连接工具
- [MobaXterm](https://moba.en.softonic.com/) -  Windows 下好用的终端连接工具
- [iTerm2](https://www.iterm2.com/) - MacOS 下最好用的终端连接工具

## 云测平台

*知名的云测平台（以及设备管理平台）*

- [STF](https://openstf.io/) - Web端知名的移动设备管理控制工具
- [Testin](https://www.testin.cn/) - 知名的商业测试平台
- [WeTest](https://wetest.qq.com/) - 腾讯质量开放平台
- [ATX-SERVER](https://github.com/openatx/atx-server) - Go语言编写的安卓设备集群管理
- [atxserver2](https://github.com/openatx/atxserver2) - ATX-SERVER 的 Python 版本

## 数据库

*常用的数据库连接工具*

- 关系型数据库
  - [Navicat](http://www.navicat.com.cn/) - 数据库可视化工具
  - [phpMyAdmin](https://www.phpmyadmin.net/) - MySQL管理平台
  - [Hue](https://gethue.com/) - 大数据交互平台
- 非关系型数据库
  - [Robo 3T](https://robomongo.org/download) - MongoDB可视化工具
  - [RDM](https://redisdesktop.com/) - Redis可视化工具

## 移动端性能

*移动端性能测试工具*

- [Monkey](https://developer.android.com/studio/test/monkey.html) - Android adb自带的稳定性测试工具
- [WeTest助手](https://wetest.qq.com/cloud/help/effective) - WeTest平台出品的APP性能数据采集工具
- [GT](https://github.com/Tencent/GT) - 腾讯开源的APP的性能监控工具
- [Emmagee](https://github.com/NetEase/Emmagee) - 网易开源的APP性能监控工具
- [PerfDog](https://perfdog.qq.com/) - 腾讯WeTest出品的性能数据采集/分析工具，支持 Android/iOS
- [Xcode Instruments](https://help.apple.com/instruments/mac/10.0/) - Xcode自带的性能调试工具集
- [SoloPi](https://github.com/alipay/SoloPi) - 支付宝开源的Android自动化工具，支持用作性能测试
- [AppCrawler](https://github.com/seveniruby/AppCrawler) - 一个 Scala 编写的 APP 自动遍历工具，支持 Android/iOS
- [UiCrawler](https://github.com/lgxqf/UICrawler) - 基于Appium的 App UI 遍历 & Monkey工具 (支持操作步骤回放)
- [Maxim](https://github.com/zhangzhao4444/Maxim) - 基于遍历规则的高性能Android Monkey

## 监控/报表

*监控和报表工具*

- [Grafana](https://grafana.com/) - Go编写的开源可视化指标监控平台
- [Sentry](https://sentry.io/welcome/) - 开源的日志记录和监控平台
- [Echart](https://echarts.apache.org/zh/index.html) - Apache开源的前端图表可视化工具
- [Allure](https://docs.qameta.io/allure/#_about) - 自动化报告生成框架（搭配 Pytest 使用）
- [HTMLTestRunnerCN](https://github.com/findyou/HTMLTestRunnerCN) - 自动化报告生成框架（搭配 unittest 使用）
- [Fabric](https://get.fabric.io/) - APP开发平台，可以监控Crash及APP版本数据
- [Tableau](https://www.tableau.com/) - 数据分析和可视化工具

## 用例设计

*用例设计常用工具*

- [Xmind](https://www.xmind.net/) - 思维脑图形式的用例编写工具
- [Excel](https://www.microsoft.com/zh-cn/microsoft-365/excel) - 表格形式的用例编写工具 
- [behave](https://pypi.org/project/behave/) - python 的 BDD 库，用例组织
- [禅道](https://www.zentao.net/) - 项目管理平台，也支持用例管理
- [kityminder](https://github.com/fex-team/kityminder) - 百度脑图开源版本，支持二开和本地化部署

## 测试环境

*测试环境维护常用工具*

- [Ansible](https://www.ansible.com/) - 流行的自动化运维工具
- [fabric](http://www.fabfile.org/) - 非编译型语言部署工具
- [Docker](https://www.docker.com/) - 开源的应用容器引擎
- [k8s](https://www.kubernetes.org.cn/k8s) - 容器化应用管理云平台解决方案
- [uWSGI](https://uwsgi-docs.readthedocs.io/en/latest/) - 一个Python Web服务器
- [Nginx](http://nginx.org/en/) - 高性能的HTTP和反向代理web服务器
- [walle](http://www.walle-web.io/) - 高颜值项目部署系统

## 持续集成

*常用的持续集成工具*

- [Jenkins](https://www.jenkins.io/) - 最主流的持续集成工具

## 项目管理

*业内常用的项目管理软件*

- [Jira](https://www.atlassian.com/software/jira) - Atlassian公司出品的项目与事务跟踪工具，也是目前最流行的项目管理工具
- [禅道](https://www.zentao.net/) - 项目管理平台
- [普兰能效平台](https://github.com/purang-fintech) - 开源的效能平台，支持本地化部署和二次开发
- [tower](https://tower.im/) - 团队和项目管理平台

## 在线文档

*工作中常用的协作工具*

- [石墨文档](https://shimo.im/desktop) - 一款轻便、简洁的在线协作文档工具
- [wiki](https://www.atlassian.com/software/confluence/why-wiki-collaboration-software) - 企业级的wiki系统
- [有道云笔记](http://note.youdao.com/) - 在线笔记
- [印象笔记](https://www.yinxiang.com/) - 在线笔记
- [Processon](https://www.processon.com/) - 在线作图工具

## 版本控制

*业内主流的代码版本管理工具*

- [Git](https://git-scm.com/) - 开源的分布式版本控制系统
- [Gitlab](https://about.gitlab.com/) - 支持本地化部署的Git项目托管平台
- [Github](https://github.com/) - 面向开源及私有软件项目的托管平台
- [Gitee](https://gitee.com/) - 码云，面向中国国内的软件项目的托管平台
- [SVN](https://tortoisesvn.net/) - 一个开放源代码的中心化的版本控制系统

## 安全测试

*业界知名的安全测试工具精选*

- [AppScan](https://www.ibm.com/developerworks/cn/downloads/r/appscan/learn.html) - IBM 网络安全测试工具
- [Nmap](https://nmap.org/) - 网络扫描和嗅探工具包
- [sqlmap](http://sqlmap.org/) - sql 注入漏洞检查工具
- [nessus](https://zh-cn.tenable.com/products/nessus?tns_redirect=true) - 目前全世界最多人使用的系统漏洞扫描与分析软件
- [Drozer]() - Android 渗透测试工具
- [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) - 移动端应用安全问题检测框架和工具（支持Android/iOS）
- [QARK](https://github.com/linkedin/qark) - Linkin 开源的一款静态代码分析工具

## 代码扫描

*业界知名的代码扫描工具*

- [SonarQube](https://www.sonarqube.org/) - 代码质量管理平台
- [QARK](https://github.com/linkedin/qark) - Linkin 开源的一款静态代码分析工具
- [ESLint](https://eslint.bootcss.com/) - JavaScript 语法规则和代码风格的检查工具
- [Jlint](http://jlint.sourceforge.net/) - Java 语法规则和代码风格的检查工具
- [p3c](https://github.com/alibaba/p3c) - 阿里巴巴 Java 代码风格检查工具
- [pylint](https://www.pylint.org/) - Python 语法规则和代码风格检查工具

# 测试框架

## 整站项目

*测试平台整站项目*

- [metersphere](https://github.com/metersphere/metersphere) - 一站式的开源企业级持续测试平台
- [普兰能效平台](https://github.com/purang-fintech) - 开源的效能平台，支持本地化部署和二次开发
- [sosotest](https://github.com/LianjiaTech/sosotest) - 贝壳找房测试团队开源的整站接口自动化测试平台，支持 HTTP 和 DUBBO
- [LuckyFrameWeb](https://gitee.com/seagull1985/LuckyFrameWeb) - 开源自动化测试平台
- [HttpRunner](https://github.com/HttpRunner/HttpRunner) - HttpRunner 是一款面向 HTTP(S) 协议的通用测试框架
- [ATX-Test](https://github.com/pengchenglin/ATX-Test) - 基于ATX-Server的UI自动化测试框架，目前也支持运行Monkey
- [APT](https://github.com/ooqitech/ATP) - Flask + vue.js 的测试服务平台

## 前端模版

- [Vue-element-admin](https://github.com/PanJiaChen/vue-element-admin) - 基于 vue.js 和 ElementUI 的后台管理系统前端脚手架项目
- [inspinia](https://github.com/Chuibility/inspinia) - 基于 Bootstrap 的后台管理系统前端框架模版
- [xenon](https://github.com/GroupOfStar/xenon) - 基于 Bootstrap 的后台管理系统前端框架模版
- [lin-cms-vue](https://github.com/TaleLin/lin-cms-vue) - 林间有风团队开源，cms后台工程，前端部分

## 后端项目

- [lin-cms-springboot](https://github.com/TaleLin/lin-cms-spring-boot) - 林间有风团队开源，cms后台工程，后端 Java
- [lin-cms-flask](https://github.com/TaleLin/lin-cms-flask) - 林间有风团队开源，cms后台工程，后端 Python
- [lin-cms-koa](https://github.com/TaleLin/lin-cms-koa) - 林间有风团队开源，cms后台工程，后端 Node.js

# 学习资源

## 视频资源

- [Python移动自动化测试面试](https://coding.imooc.com/class/182.html) - 慕课网无线测试面试

## 学习路线

- [测开学习路线] - 从0开始，入职大厂测试开发学习路线
- [测试开发技术图谱](https://camo.githubusercontent.com/d1064bfadc97d2a7f3491aa4c6e545a9aba8ea66/687474703a2f2f7777312e73696e61696d672e636e2f6c617267652f36396235373764346779316735726471636372366c6a32307a6b316561616c302e6a7067) - 霍格沃滋测试学院出品

## 测试书籍

- [测试开发必读书单] - 软件测试必读的本书

## 编程学习

- [菜鸟教程](https://www.runoob.com/) - 基本上涵盖了大多数的主流编程语言的教程
- [廖雪峰Python](https://www.liaoxuefeng.com/wiki/1016959663602400) - python基础知识教程，学完应该能入门了
- [Python3高级核心技术97讲](https://coding.imooc.com/class/200.html) - 慕课网 Python 进阶最优视频
- [廖雪峰Git](https://www.liaoxuefeng.com/wiki/896043488029600) - 优质 Git 教程
- [How2J](https://how2j.cn/) - 优质 Java 教程
- [Mall](https://github.com/macrozheng/mall) - 优质Java项目，SpringBoot + Mybatis
- [JavaGuide](https://github.com/Snailclimb/JavaGuide) - 「Java学习+面试指南」一份涵盖大部分Java程序员所需要掌握的核心知识。
- [JavaGuide 面试突击版](https://github.com/Snailclimb/JavaGuide-Interview) - Java 面试突击版  

## 面试相关

- [牛客网](https://www.nowcoder.com/) - 刷题、面经
- [leetcode](leetcode) - 算法学习、算法面试题
- [500丁简历](https://www.500d.me/) - 简历模版
- [ResumeSample](https://github.com/geekcompany/ResumeSample) - 程序员简历模版
- [冷熊简历](http://cv.ftqq.com/?fr=github) - 冷熊简历md格式 

# 测试网站

## 测试社区

- [CSDN](https://www.csdn.net/) - 中国专业IT社区
- [TesterHome](https://testerhome.com/) - 中国最好的测试社区
