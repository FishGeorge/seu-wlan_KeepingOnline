# SeuKeeper
Used name: Seu-Wlan_KeepingOnline
## Introduction
&emsp;&emsp;为饱受 [seu-wlan时不时掉线，每次打开电脑都要重新输入密码登录] 的痛苦的同学们提供一个解决方案：一个用于检测电脑是否联网（通过seu-wlan），且脱机时将自动登录seu-wlan的Java程序。<br>
&emsp;&emsp;目前开发正处于测试阶段，代码还没有完整良好的封装，~~程序还没有简洁好看的GUI。最惨的是，除了开发者自己，也没有用户。~~<br>
&emsp;&emsp;E-mail: gongcheng3c@foxmail.com

---
## Install
coming soon

---
## Usage
coming soon

---
## Release Notes
时间|版本|内容
:--|:--|:--
2018.6.22|v0.0|诞生于另一个小项目的Origin版本
2018.8.2|v0.1|独立成档，做成一个桌面应用
2018.8.5|v0.2|#&ensp;修复了login动作成功后程序结束的bug<br>#&ensp;Console输出内容添加了时间戳
2018.8.17|v0.3.0|新增了对密码的base64加密功能，再也不用翻http控制台啦
2018.9.18|v0.4.0|#&ensp;开始基于Java Swing框架的界面开发，已有雏形demo
2018.9.19|v1.0.0|#&ensp;大体完成了UI设计和其初步开发<br>#&ensp;已可在UI进行登录操作
2018.11.4|v1.0.1|#&ensp;新增了注销功能<br>#&ensp;新增了联系方式与署名到“关于”页（万一出名了？）
2018.11.16|v1.0.2|项目预备移植到JavaScript，转向Electron框架中开发。（！该版本无实质迭代，只修改了Github上项目结构。）
2018.11.22|v1.0.3-alpha|移植了UI到Electron框架下（无交互逻辑）
2018.11.27|v1.0.3-alpha.2|#&ensp;重新设计了UI，进度70%<br>#&ensp;核心逻辑（指登录）移植完毕
2018.11.30|v1.0.3|#&ensp;添加了托盘图标及其右键菜单<br>#&ensp;添加了本地数据库(electron-store)以存储账密及设置<br>#&ensp;主线程login逻辑添加了判断seu连接状态的部分<br>#&ensp;Author现可单击弹出git仓库网页<br>#&ensp;as及al功能仍无效，登录提示暂用alert()框
2018.12.11|v1.0.4-alpha|#&ensp;添加了UI登录状态页（及动画效果），但登录逻辑完整及正确性尚待检查<br>#&ensp;注销功能待移植<br>#&ensp;main进程与UI进程的as与al值有矛盾存在，窗口初始化时的读取就有问题<br>#&ensp;as及al功能仍然无效，登录提示用p_tip尚未完成
2018.12.13|v1.0.4-alpha.2|#&ensp;修复了as及al值的之前存在的冲突，作者说这块8可能再出问题<br>#&ensp;实现了保持登录（正所谓Keeper）的逻辑，尚待测试<br>#&ensp;注销功能仍然待移植<br>#&ensp;as功能仍然无效，登录提示用p_tip尚未完成。但是al的一半可以用了（定义：自动登录=打开程序时若未登录则自动登录（须开机自启<=没写））<br>#&ensp;添加了一些console输出时间戳记录
2018.12.16|v1.0.4|#&ensp;实现了注销功能<br>#&ensp;保持登录的逻辑小幅修改后基本通过测试<br>#&ensp;as功能仍然无效，登录提示用p_tip尚未完成。

---
## To do
#&ensp;√&ensp;赶紧写一个UI，要好看一点的<br>
~~#&ensp;&ensp;&ensp;打java环境和安装包~~<br>
~~#&ensp;&ensp;&ensp;优化程序内存占用...~~<br>
#&ensp;&ensp;&ensp;推广一下这个可怜的小程序<br>
#&ensp;&ensp;&ensp;记得写doc

---