---
layout: instruction
title: Instruction
tags:
---
# 说明

[Back](../../)


***本分享原则上不直接提供资源本身***
当然，这话我自己都不信

## 资源获取

本分享以保持分享内容长期存活可用为主要目标，没有考虑下载速度和便捷程度等问题。基于此目的，本分享使用的分享形式需要保证存储文件的网站尽可能长期存活，尽量不依赖分享者账号，获取资源时限制尽可能少等要求。
本分享中使用的分享形式主要有度云秒传链接和BT链接。两者能保证中长期时间内文件存活，且基本不依赖分享者账号。另部分文件附有NoPayStation的链接，这个网站短期内应该不会关门或和谐，且能保证基本的下载速度，可以选择使用。
### 度云秒传链接

度云秒传链接的使用请参考 [秒传链接提取 （greasyfork）](https://greasyfork.org/zh-CN/scripts/424574)
此种分享形式需要使用百度云账号获取，且网页版和脚本版均需要获取百度云账号的token，是否可信请自行判断。
### BT

BT的使用请参考 [BitTorrent 简介（知乎）](https://zhuanlan.zhihu.com/p/364041702)
## 压缩包与解压缩
### 压缩包格式

很遗憾，个人没有什么精力把所有的压缩包统一整理一遍，多数的压缩包都保持了出处的原样。
资源中同时存在7z、zip、rar等格式，也有一些采用了分卷压缩，请自行分辨。
如果压缩包有密码，请查看表格中的注释一栏或压缩包注释。
### 解压缩工具

PC端推荐使用7-zip、Bandizip、WinRAR等解压缩工具，Android端推荐使用ZArchiver，其他的应该也可以，如果有问题请尝试尝试使用推荐的软件。部分rar格式的压缩包可能使用了rar5格式，如果无法打开请尝试使用WinRAR5以上版本。
[7-Zip（官网）](https://www.7-zip.org/)
[Bandizip（官网）](https://www.bandisoft.com/bandizip/)
[WinRAR（官网）](https://www.win-rar.com/start.html?&L=7)
[ZArchiver（GooglePlay）](https://play.google.com/store/apps/details?id=ru.zdevs.zarchiver)
## 游戏运行
### PC（Windows）

对于硬盘版，直接解压缩运行即可。镜像版需要使用虚拟光驱加载镜像，安装后运行，可能需要保持虚拟光驱在后台运行。部分老游戏可参考 [KID社游戏PC版整理和运行状况 报告（Bilibili）](https://www.bilibili.com/read/cv12196499)
### FC/NES

测试所用模拟器为FCEUX和qFCEUX。游戏均可正常运行。
模拟器可以加载NES文件和FDS文件。
加载FDS磁碟机游戏需要额外的BIOS文件，参考 [link（FCEUX 官网）](https://fceux.com/web/help/FamicomDiskSystem.html)。 原则上BIOS文件需要用户自行从真机中Dump，下同。
[FCEUX（官网）](https://fceux.com/web/home.html) [FCEUX（Github）](https://github.com/TASEmulators/fceux)
### SFC/SNES

测试所用模拟器为BSNES。SFC格式的游戏可以正常运行。
模拟器理论上还可以运行BS-X游戏，但由于一些原因无法运行。
[BSNES（Github）](https://github.com/bsnes-emu/bsnes)
### GameBoy、WonderSwan、NeoGeoPocket

未测试。理论上可用。
### Sega Saturn

测试所用的模拟器为SSF。只测试了游戏《6 inch my darling》，可以正常运行。
模拟器需要另行加载BIOS文件。
[SSF（CoolROM）](https://coolrom.com.au/emulators/saturn/68/SSF.php)
### PlayStation1

测试所用的模拟器为DuckStation。测试了《Infinity》、《镰鼬之夜》等几个游戏，可以正常运行。
模拟器需要另行加载BIOS文件。
[DuckStation（官网）](https://www.duckstation.org/)  [DuckStation（GooglePlay）](https://play.google.com/store/apps/details?id=com.github.stenzek.duckstation)
### Sega DreamCast

测试所用的模拟器为NullDC。测试了《Ever17》（BIN/CUE）、《Ever17 Premium Edition》（CDI）、《Erde》（BIN/CUE）等几个游戏，可以正常运行。由于这个模拟器只支持CDI格式或GDI格式，不支持BIN/CUE格式（redump标准），所以还需要用额外的工具gdidrop来将BIN/CUE格式转化为GDI格式。
模拟器需要另行加载BIOS文件。
[NullDC（GitHub）](https://github.com/skmp/nulldc)（只有源码） [NullDC（CoolROM）](https://coolrom.com.au/emulators/dc/89/nullDC.php) [NullDC（官网）](https://segaretro.org/NullDC)
[gdidrop（GitHub）](https://github.com/feyris-tan/gdidrop)
### PlayStation2

测试所用模拟器为PCSX2。测试了多个游戏，均可正常运行。其中《Never7 SuperLite1500版》由于未知原因会卡在开头的启动动画，需要禁用MPEG解码才能正常启动。
PCSX2近期开始推出了1.7版本更新，在新版本中有些游戏反而不能正常运行，如出现此问题请先尝试使用1.6版本。
目前安卓端也推出了模拟器AetherSX2。Bug比较多，已经能正常运行大部分游戏。
本分享中的所有游戏均为ISO格式，在以上两个模拟器中被支持。AetherSX2模拟器在推广使用CHD格式的游戏，此格式能提供相比 ISO格式更高的压缩率和读取速度，PCSX2 1.7版本也支持了这一格式。
模拟器需要另行加载BIOS文件。
[PCSX2（官网）](https://pcsx2.net/) [PCSX2（CoolROM）](https://coolrom.com.au/emulators/ps2/57/PCSX2.php)
[AetherSX2（官网）](https://www.aethersx2.com/) [AetherSX2（GooglePlay）](https://play.google.com/store/apps/details?id=xyz.aethersx2.android)
### PlayStation Portable

测试所用模拟器为PPSSPP。模拟器已较为成熟。测试了多个游戏，均可正常运行。
[PPSSPP（官网）](https://ppsspp.org/) [PPSSPP（CoolROM）](https://coolrom.com.au/emulators/psp/102/PPSSPP.php)
### Xbox360

测试所用模拟器为xenia。测试了几乎所有收集到的游戏。其中《Disorder6》、《Muv-Luv》系列等rUGP引擎的游戏能进 入游戏，但是无法加载图片，只能盲打，相当于无法进行游戏。
Xbox360游戏常用ISO格式、GOD格式、XEX格式、XBLA格式。ISO格式为光盘镜像格式，可细分为redump标准的镜像和从GOD、XEX格式重构的镜像。redump标准的ISO镜像大小约为7.3G，压缩后约6.5~6.9G，理论上完整保留了光盘中的所有信息和冗余。重构镜像体积较小，一般也能包含游戏的所有有效信息，但有时无法正确解压提取内容。如果需要提取游戏资源建议使用redump镜像。Xbox360的ISO格式是一种特殊的格式，与其他平台的ISO格式大有不同，不能使用一般解压缩工具或虚拟光驱打开，也不要以此判断 镜像是否损坏。GOD格式全称Games On Demand，是游戏存储在Xbox360的硬盘上的格式，其形式类似于分卷压缩，一般体积略小于ISO格式的重构镜像和XEX格式。此格式可使用工具从ISO格式转化得到，或使用工具转化为ISO格式重构镜像。XEX格式实际上指Xbox360平台的可执行文件格式，相当于Windows下的EXE格式，是游戏真实存在的形式，可从ISO格式提取得到。此格式的游戏一般通过JTAG破解得到，所以有时也称为JTAG格式。 XBLA格式全称Xbox Live Arcade，是一类只能从网络商店下载的游戏，与另三种格式无关。
模拟器能加载GOD格式、ISO格式、XEX（收集中称为unpacked）格式的游戏。XBLA格式似乎也能正常运行，但无法联机对战。
此后的模拟器会开始非常吃性能，需要较高的电脑配置。
[xenia（官网）](https://xenia.jp/)
### PlayStation3

测试所用的模拟器为RPCS3。测试了几乎所有收集到的游戏，在最新版本下均可正常运行。模拟器能加载unpacked格式和PKG格式的游戏。对于PKG格式的游戏，需要先安装rap文件用于解密，再安装PKG文件。PS3平台也有redump标准的ISO格式镜像，但在此标 准下镜像会保留加密，不便使用，此格式的分享也很少，故没有收集。
模拟器需要另行加载系统固件PS3UPDAT.PUP，可前往PlayStation官网下载。不同地区的版本可能有所不同，未具体测试。
[RPCS3（官网）](https://rpcs3.net/)
[PS3UPDAT（PlayStation 美国）](https://www.playstation.com/en-us/support/hardware/ps3/system-software/) [PS3UPDAT（PlayStation 台湾地区）](https://www.playstation.com/zh-hant-tw/support/hardware/ps3/system-software/) [PS3UPDAT（PlayStation 日本）](https://www.playstation.com/ja-jp/support/hardware/ps3/system-software/)
### PlayStation Vita

测试所用的模拟器为Vita3k。这个模拟器仍处于初级阶段，游戏稍微复杂一点就可能无法运行，多数游戏应该无法正常通关。在游戏中快进的 话有概率闪退，注意及时保存。
模拟器目前更新到了0.1.5版本，可用性有了不少提升，应该有不少游戏已经可以基本正常的运行。

PCSG01021 \[OCCULTIC;NINE]（日版） 可以进入游戏。文字无法显示，画面显示有一些问题。
PCSG00995 \[CHAOS;CHILD らぶchu☆chu!!] （日版，可打汉化补丁）可以进行游戏。视频、音频bug和一个固定闪退bug已解决。动画效果稍有问题。

0.1.3版本时测试的几个可用或部分可用的游戏列举如下。

PCSG00995 \[CHAOS;CHILD らぶchu☆chu!!] （日版，可打汉化补丁）禁用视频解码后可进入游戏。画面正常，音频无法正常播放，听起来像是噪音一样。经常莫名其妙闪退。
PCSG01183 \[メモリーズオフ -Innocent Fille-]（日版） 可以进行游戏。柚莉DLC未测试。
PCSH10133 \[MemoriesOff -Innocent Fille-] （亚版中文）可以进行游戏。
PCSG01264 \[MEMORIES OFF -INNOCENT FILLE- FOR DEAREST] （日版中文）可以进行游戏。
PCSG00177 \[メモリーズオフ ゆびきりの記憶]（日版） 可以进行游戏。
PCSG00176 \[メモリーズオフ6 Complete]（日版） 可以进行游戏。由于游戏内实际上分为三个部分，在不同部分之间跳转时会关闭当前窗口新开另一个窗口，重新加载缓存。
PCSG01007 \[かまいたちの夜 輪廻彩声]（日版）可以进行游戏。

模拟器能加载PKG格式和MaiDump格式的游戏。对于PKG格式的游戏，需要加载work.bin文件或输入zRIF才能解密安装。模拟器名义上能加载NoNPDRM格式的游戏，但实际上不能，需要注意。模拟器不能加载VitaminDump格式的游戏。
模拟器需要另行加载系统固件PSP2UPDAT.PUP。不同地区的版本可能有所不同。
[Vita3k（官网）](https://vita3k.org/) [Vita3k（GitHub）](https://github.com/Vita3K/Vita3K)
### Nintendo Switch

目前有Ryujinx和yuzu两个主流模拟器。两个模拟器的表现可以说不相上下。如果你需要在较低性能的设备上运行游戏，推荐使用yuzu的Vulkan模式，以获得较为流畅的体验。如果需要运行含有大量3D建模、需要文本输入的游戏，推荐使用Ryujinx以避免一些Bug。一般推荐同时安装这两个模拟器，在其中一个出现问题时可以再试一下另一个。
Switch游戏常使用XCI格式和NSP格式。XCI格式接近于卡带镜像，可以在一个文件内同时包含游戏本体、更新补丁、DLC等，甚至可以在一个XCI文件里包含多个游戏。NSP格式接近于游戏程序包，一般只能包含一个游戏本体或一个更新补丁。两种格式间可以几乎无损的转换、整合、分解。模拟器可以读取或安装XCI格式的游戏整合包，读取或安装NSP格式的游戏本体，但NSP格式的更新补丁、DLC必须安装后才能运行。另有XCZ、NSZ格式，由以上两种格式压缩得到，可以无损解压还原，模拟器不能直接读取这种格式。综上，Switch游戏不必区分格式。
模拟器需要另行加载系统固件和游戏密钥。
[Ryujinx（官网）](https://ryujinx.org/) [yuzu（官网）](https://yuzu-emu.org/) [yuzu（pinEApple@Github）](https://pineappleea.github.io/)
### 各个平台固件获取

从网络获取系统固件可能引发版权问题，请自行考虑。
[Darthsternie's Firmware and Exploits Archive](https://darthsternie.net/)
[CoolROM](https://coolrom.com.au/bios/)
[RetroPieBIOS（Github）](https://github.com/archtaurus/RetroPieBIOS)



[Back](../../)