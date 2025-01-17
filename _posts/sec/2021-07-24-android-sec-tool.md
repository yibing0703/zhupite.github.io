﻿---
layout:		post
category:	"sec"
title:		"Android安全工具-安卓安全工具汇总"
tags:		[android]
---
- Content
{:toc}
**关键词**：安卓破解工具，安卓逆向工具，安卓黑客工具，安卓安全工具，Android破解工具，Android逆向工具，Android黑客工具，Android安全工具。

- [好物推荐：移动端开发安全工具](https://www.oschina.net/project/awesome?columnId=14)



# 审计测试

| 名称                                                | 简介                                                         | 相关资料                                                 |
| --------------------------------------------------- | ------------------------------------------------------------ | -------------------------------------------------------- |
| virustotal                                          |                                                              | https://www.virustotal.com/                              |
| MobSF                                               | 移动安全框架 (MobSF) 是一个自动化、一体化的移动应用程序 (Android/iOS/Windows) 渗透测试、恶意软件分析和安全评估框架，能够执行静态和动态分析（动态分析目前只支持 Android）。 | https://github.com/MobSF/Mobile-Security-Framework-MobSF |
| appmon                                              | 隐私检测、安全检测、HOOK函数调用、行为分析等可以借助这个框架 | [appmon](https://github.com/dpnishant/appmon)            |
| [apkleaks](https://github.com/dwisiswant0/apkleaks) | APKLeaks 是一个开源的 apk 文件敏感信息扫描工具，通过扫描 APK 文件来获取 URI、端点和 secret 信息。APKLeaks 使用起来非常方便，通过简单的命令行即可完成 APK 文件的信息提取，而且支持通过配置 Json 文件来调整敏感信息的搜索规则，输出结果支持 txt 和 Json 两种格式（默认生成 txt 格式）。依赖于逆向工程工具 jadx。 |                                                          |
| [XPrivacyLua](https://github.com/M66B/XPrivacyLua)  | 隐私权限相关。撤销应用程序的 Android 权限通常会导致应用程序崩溃或出现故障。XPrivacyLua 通过向应用程序提供虚假数据而不是真实数据来解决这个问题。 |                                                          |
| [Adhrit](https://github.com/abhi-r3v0/Adhrit)       | Adhrit 是一个开源的 Android APK 逆向和分析套件，可提取 APK 文件中的重要信息，并使用 Ghera 基准来识别 Android 应用程序中可能存在的漏洞。Adhrit 深入分析 APK 文件的静态字节码，它依赖 Python3 和 JDK ，自带 GUI 界面，启动时会生成可以上传 APK 并生成报告的 Web 界面，分析完毕会生成 Json 格式的分析报告。 |                                                          |
| [QARK](https://github.com/linkedin/qark)            | QARK 全称 Quick Android Review Kit ：快速 Android 审查工具包，这个工具可用来检查 Android 应用的源代码和打包的 APK 中常见的安全漏洞。 |                                                          |
| [MARA](https://www.oschina.net/p/mara)              | MARA 是一个移动应用程序逆向工程和分析框架。它将常用的移动应用逆向工程和分析工具组合在一起，用于测试移动应用，以抵御 OWASP（开放式 WEB 应用程序安全项目）的移动安全威胁。MARA 支持 APK 逆向工程，比如将 Dalvik 字节码反汇编为 smali 字节码或 Java 字节码，同时还支持 APK 反混淆、APK 执行路径、IP 地址、URL、URI、电子邮件等基本信息的提取、APK 漏洞扫描、恶意软件分析、APK Manifest 分析等多种功能。MARA 还提供基于 OWASP Top Mobile Top 10 和 OWASP Mobile Apps Checklist 的源代码静态分析，能够对 apk、dex 或 jar 文件执行 单个或 批量分析。 |                                                          |
| [AndroL4b](https://www.oschina.net/p/androl4b)      | AndroL4b 是一个基于 ubuntu-mate 的安卓安全虚拟机，可用于逆向工程和恶意软件分析。AndroL4b 包括来自不同信息安全极客和研究人员的最新框架、教程和漏洞实验室的集合，上文提到的 Radare2 、APKTools、ByteCodeViewer、Qark 、MARA 等工具，AndroL4b 均已内置。同时还有 Android Security Sandbox 、InsecureBankv2 等漏洞实验室，可提供最新 Android 漏洞的详细信息。 | https://sourceforge.net/projects/androl4b/               |



# 综合工具

| 名称                                              | 简介                                                         | 相关资料                                                     |
| ------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 安卓右键工具                                      | 集成到Windows系统菜单，右键操作安卓相关，方便快捷。          | [APKmenuTOOL - 安卓右键工具](https://github.com/bigsinger/APKmenuTOOL)、[CustomContextMenu: 自定义Windows系统右键菜单工具](https://github.com/bigsinger/CustomContextMenu) |
| AndLayoutInspector                                | 安卓界面布局获取分析工具（uiautomation tool），C#语言编写。  | [界面布局分析 AndLayoutInspector](https://github.com/inckie/AndLayoutInspector) |
| AppMethodOrder                                    | 一个能让你了解所有函数调用顺序以及函数耗时的Android库（无需侵入式代码） | [AppMethodOrder](https://github.com/zjw-swun/AppMethodOrder) |
| apk-signature-verify                              | Python校验apk签名，jar Signature / APK Signature v2 verify with pure python (support rsa dsa ecdsa) | [apk-signature-verify](https://github.com/shuxin/apk-signature-verify) |
| AmBinaryEditor                                    | AndroidManifest二进制修改工具。新增、修改、删除指定名字的tag或者该tag的attr | [AmBinaryEditor（AndroidManifest二进制修改工具介绍）](http://ele7enxxh.com/AndroidManifest-Binary-Editor.html)、[AndroidManifest二进制文件格式分析](https://bbs.pediy.com/thread-194206.htm) |
| MT管理器                                          | 文件管理、APK编辑功能，在手机上高效地进行各种文件操作以及修改安卓软件。 | [MT管理器](http://binmt.cc)                                  |
| AndroidManifestFix                                | AndroidManifest.xml文件修复工具。用于修复AXML文件中属性名称缺失的问题。 | https://github.com/zylc369/AndroidManifestFix                |
| NP-Manager                                        | 超级混淆                                                     | https://github.com/githubXiaowangzi/NP-Manager               |
| FreeProGuard                                      | Config proguard for common Android libraries.                | https://github.com/Blankj/FreeProGuard                       |
| [BlackBox](https://github.com/FBlackBox/BlackBox) | BlackBox（黑盒）是一款虚拟引擎，可以在 Android 上克隆和运行虚拟应用，拥有免安装运行能力。黑盒可以控制被运行的虚拟应用，做任何想做的事情。 |                                                              |
| 太极                                              | 多开器、虚拟空间                                             |                                                              |
| VirtualApp                                        |                                                              |                                                              |
| AssetStudio                                       | unity游戏破解工具：AssetStudio is a tool for exploring, extracting and exporting assets and assetbundles. | https://github.com/Perfare/AssetStudio                       |
| r0capture                                         | 安卓应用层抓包通杀脚本                                       | https://github.com/r0ysue/r0capture                          |
| StrandHogg 2.0                                    | New serious Android vulnerability                            | https://promon.co/resources/downloads/strandhogg-2-0-new-serious-android-vulnerability/ |
| 安卓应用的安全和破解                              | 一个汇总安卓安全的博客小站                                   | https://book.crifan.com/books/android_app_security_crack/website/ |
| radare2                                           | UNIX-like reverse engineering framework and command-line toolset。可以逆向分析dex/so/二进制等文件 | https://github.com/radareorg/radare2                         |
|                                                   |                                                              |                                                              |



# 反编译工具

| 名称                                                         | 简介                                                         | 相关资料                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| IDA                                                          |                                                              | https://www.hex-rays.com/products/ida/news/ 、 https://www.hex-rays.com/products/ida/ 、 https://ida2020.org/ |
| jadx                                                         | JADX 是一个 Dex 到 Java 的反编译器， 用于从 Android Dex 和 Apk 文件生成 Java 源代码，有命令行和 GUI 两个版本。JADX 的主要功能是从 APK、dex、aar、aab 和 zip 文件将 Dalvik 字节码反编译为 java 类，自带去混淆器。JADX-GUI 版本还支持以高亮语法查看反编译的代码、提供用法指引、全文检索和 smali 调试器等功能。 | [jadx: Dex to Java decompiler](https://github.com/skylot/jadx) |
| JEB                                                          |                                                              | https://www.pnfsoftware.com/                                 |
| Apktool                                                      | Apktool 是一个用于逆向工程第三方、封闭二进制 Android 应用程序的工具。它可以用来从 Android 的 apk 安装程序中提取各种资源，将资源分解为几乎原始的形式（比如 resources.arsc、classes.dex和 9.png.XMLs），并对这些资源进行修改和重新打包。Apktool 可用于 也可将解码的资源重建回二进制 APK/JAR 文件，由于它支持自动化的 APK 构建，因此也可以用来完成一些重复的 APK 构建任务。Apktool 可用于应用的本地化、往应用中添加一些功能、使应用支持自定义平台、或分析学习应用程序内部结构等用途， 不适用于盗版和其他非法用途。 | https://github.com/iBotPeaches/Apktool                       |
| smali/baksmali                                               |                                                              | [smali: smali/baksmali](https://github.com/JesusFreke/smali) |
| dex2jar                                                      | Tools to work with android .dex and java .class files        | https://github.com/pxb1988/dex2jar                           |
| jd-gui                                                       | A standalone Java Decompiler GUI                             | https://github.com/java-decompiler/jd-gui                    |
| Luyten                                                       | An Open Source Java Decompiler Gui for Procyon               | https://github.com/deathmarine/Luyten                        |
| reko                                                         | C#开源项目-二进制文件的反编译器                              | https://github.com/uxmal/reko                                |
| GDA                                                          | GJoy Dex Analyzer(GDA)，中国第一款也是唯一一款全交互式的现代反编译器，同时也是世界上最早实现的dalvik字节码反编译器。 GDA不只是一款反编译器，同时也是一款轻便且功能强大的综合性逆向分析利器，其不依赖java且支持apk, dex, odex, oat, jar, class, aar文件的反编译， 支持python及java脚本自动化分析。其包含多个由作者独立研究的高速分析引擎:反编译引擎、漏洞检测引擎、 恶意行为检测引擎、污点传播分析引擎、反混淆引擎、apk壳检测引擎等等 | http://www.gda.wiki:9090/                                    |
| TTDeDroid                                                    | 一键反编译工具(不需要手动安装Python) One key for quickly decompile apk/aar/dex/jar, support by jadx/dex2jar/enjarify. | https://github.com/tp7309/TTDeDroid                          |
| Smali2JavaUI                                                 | tool-pc-windows-gui-smali2java-a-tool-decompile-smali-to-java | https://forum.xda-developers.com/showthread.php?t=2430413    |
| Bytecode Viewer                                              | Bytecode Viewer (字节码查看器) 是一个高级轻量级 Java/Android 逆向工程套件，可以分析 Java 8+ Jar 文件 和 Android APK 文件。Bytecode Viewer 内置 6 个 Java 反编译器：Krakatau、CFR、Procyon、FernFlower、JADX、JD-GUI；和 3 个内置字节码反汇编器，包括 2 个汇编器：Krakatau 和 Smali/BakSmali ；以及 Dex2Jar 和 Enjarify 这两个 APK/DEX 转换器，同时拥有高级搜索、调试等功能。 | https://github.com/Konloch/bytecode-viewer                   |
| wxUnpacker                                                   | 小程序反编译工具 , 现已被封，但有其他fork版本                | https://github.com/geilige/wxappUnpacker                     |
| ManifestEditor                                               | modify Android Manifest binary file.                         | https://github.com/WindySha/ManifestEditor                   |
| [x-DecompilerWxApkgTool](https://gitee.com/xwintop/x-DecompilerWxApkgTool) | DecompilerWxApkgTool是使用javafx开发的一款微信小程序反编译工具，从微信小程序（小游戏）中获取压缩包，反编译其中的编码及资源 |                                                              |

- [android-classyshark: Analyze any Android/Java based app or game](https://github.com/google/android-classyshark)
- [Krakatau: Java decompiler, assembler, and disassembler](https://github.com/Storyyeller/Krakatau) java的反编译器、汇编器、反汇编器
- [androguard/androguard: Reverse engineering, Malware and goodware analysis of Android applications)](https://github.com/androguard/androguard)



# HOOK工具

| 名称            | 简介                                                         | 相关资料                                             |
| --------------- | ------------------------------------------------------------ | ---------------------------------------------------- |
| frida           |                                                              | https://github.com/frida/                            |
| Cydia Substrate |                                                              | http://www.cydiasubstrate.com/                       |
| Xposed          |                                                              |                                                      |
| EDXposed        |                                                              |                                                      |
| LSPosed         | 完全取代EDXposed                                             |                                                      |
| VirtualXposed   |                                                              |                                                      |
| FakeXposed      | Xposed隐藏器                                                 |                                                      |
| JustTrustMe     | 基于Xposed写的可以绕过SSL Pinning检测的工具                  | https://github.com/Fuzion24/JustTrustMe              |
| Inspeckage      | 基于Xposed写的动态分析工具，Hook了大量逆向时常见的方法，如Crypto、Hash，这两个类型在破解大部分APP的加密参数时可以说是降维打击，因为大部分APP的加密参数都逃不过MD5、SHA1、AES、DES这四种，而它们都被Hook了（不仅仅只有这四种）。基本上就是打开Inspeckage再打开它的Web端，然后打开指定的APP操作一下，一个搜索，加密参数就原形毕露了 | https://github.com/ac-pm/Inspeckage                  |
| Objection       | objection是基于Frida的一个工具,可以方便我们直接找出apk中需要HOOK的方法，还可以打印函数的参数、返回值以及栈调用等，是辅助编写Frida脚本的好工具。 | https://github.com/sensepost/objection               |
| PMS AMS HOOK    | 插件化框架 PMS AMS HOOK。demos to help understand plugin framwork | https://github.com/tiann/understand-plugin-framework |
| UCrack          | 基于Xposed写的辅助工具，集成了自动网络抓包、网络堆栈爆破、文件日志、WebView调试环境、自动脱壳、Native函数注册监控、记录程序自杀堆栈等功能 |                                                      |

- [Android-Inline-Hook](https://github.com/ele7enxxh/Android-Inline-Hook)

- [xHook: 🔥 A PLT hook library for Android native ELF.](https://github.com/iqiyi/xhook)

- [bytedance/bhook](https://github.com/bytedance/bhook)：bhook(aka ByteHook) 是一个针对 Android app 的 PLT hook 框架。字节跳动的大多数 Android app 在线上使用了 bhook 作为 PLT hook 方案。

  

# 脱壳工具

- [BlackDex](https://github.com/CodingGay/BlackDex): BlackDex是一个运行在Android手机上的脱壳工具，支持5.0～12，无需依赖任何环境任何手机都可以使用，包括模拟器。只需几秒，即可对已安装包括未安装的APK进行脱壳。
- [ApkPecker自动化DEX-VMP脱壳功能全新上线](https://mp.weixin.qq.com/s/ppnvwwd9k6hP_xK364ydfg)（腾讯科恩实验室），[ApkPecker脱壳服务FAQ](https://docs.qq.com/doc/DRmVBbWtHcmNPYWxO)，[ApkPecker](https://apkpecker.qq.com/)（面向攻击面的Android应用自动化检测系统）
- [AUPK](https://bbs.pediy.com/thread-266716.htm)：基于Art虚拟机的脱壳机，[AUPK](https://github.com/FeJQ/AUPK)，[DexPatcher: 修复脱壳后的dex文件](https://github.com/FeJQ/DexPatcher)
- [FRIDA-DEXDump: Fast search and dump dex on memory.](https://github.com/hluwa/FRIDA-DEXDump)
- [frida-unpack: 基于Frida的脱壳工具](https://github.com/dstmath/frida-unpack)
- [unpacker](https://github.com/youlor/unpacker): 基于ART主动调用的脱壳机
- [将FART和Youpk结合来做一次针对函数抽取壳的全面提升](https://bbs.pediy.com/thread-260052.htm)
- 安卓查壳工具：[rednaga/APKiD: Android Application Identifier for Packers, Protectors, Obfuscators and Oddities - PEiD for Android](https://github.com/rednaga/APKiD)
- Xposed反射大师 脱壳
- [DumpDex: 💯一款Android脱壳工具，需要xposed支持, 易开发已集成该项目](https://github.com/WrBug/dumpDex)  用来从运行中的安卓app中导出dex文件的工具。
- [strazzere/android-unpacker: Android Unpacker presented at Defcon 22: Android Hacker Protection Level 0](https://github.com/strazzere/android-unpacker)
- [zyq8709/DexHunter: General Automatic Unpacking Tool for Android Dex Files](https://github.com/zyq8709/DexHunter)
- FDex2：用来从运行中的安卓app中导出dex文件的工具
- [drizzleDumper: drizzleDumper是一款基于内存搜索的Android脱壳工具。](https://github.com/DrizzleRisk/drizzleDumper)
- [DexExtractor 用于破解邦邦加密的安卓dex文件提取器](https://github.com/lambdalang/DexExtractor)
- [FUPK3](https://github.com/F8LEFT/FUPK3): 演示视频https://pan.baidu.com/s/1HH_-TQGca1NLoSqzvOPB3Q 密码：izm3
- [drizzleDumper](https://github.com/DrizzleRisk/drizzleDumper#drizzledumper): drizzleDumper是一款基于内存搜索的Android脱壳工具。
- [DexHunter](https://github.com/zyq8709/DexHunter): General Automatic Unpacking Tool for Android Dex Files
