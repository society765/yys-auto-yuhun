
# 阴阳师自动御魂脚本

网易阴阳师电脑版，按键精灵9脚本，自动御魂。

This is a script, written using Anjianjingling 9, for automated Yuhun farming in Netease game Onmyoji, PC emulator version. 

## 准备工作

玩家需自行下载网易阴阳师电脑版，并登陆至游戏内。

该脚本为本人修仙时间使用按键精灵9.21.10865版本编写，玩家需自行下载按键精灵，并将代码 [yys-auto-yuhun.Q](yys-auto-yuhun.Q) 拷贝后导入使用。

## 使用方法及功能简介

玩家需要先进入探索灯笼-御魂-八歧大蛇-十层界面（或你想要挂机的层数），并且将鼠标指针置于阴阳师窗口内，然后可以使用键盘快捷键(默认 F10)开始运行脚本，之后可以将鼠标移走。由于使用了找色函数，所以阴阳师窗口全程不能被遮挡，可能会在将来更新为后台找色。该脚本使用了鼠标后台点击函数，所以在运行过程中不会有鼠标漂移或乱点现象。

第一次进入御魂战斗时，脚本会延迟约5s，目的为找色并记录，请勿在此过程移动或遮挡窗口。

该脚本为单人探索，每次消耗6体力。默认设定是全程点中间怪物，玩家也可以设定为全程点右边怪物，或不点怪。可以通过注释掉对应的语句实现。

玩家需要开启自动战斗模式，并提前准备好战斗阵容。御魂十层界面中的阵容不需要锁定。

在御魂战斗过程中，该脚本会自动拒绝所有悬赏封印的邀请。

该脚本仅使用了画面找色，鼠标后台点击的函数，完全模拟人类玩家行为，没有使用任何内存读写函数。在敏感位置添加了均匀分布的随机时间漂移，和随机坐标漂移。作者使用过该脚本几千体力仍没有收到鬼使黑来信，而且作者不对您的可能存在的任何被封禁结果负责。  

玩家可以通过修改stx,sty变量来修改阴阳师窗口左上角的位置。

玩家可以在任何时刻使用键盘快捷键结束脚本(默认 F12)。

感谢您使用该脚本，并欢迎各种反馈和改进意见。 

## 已知存在的问题

*  暂无
*  作者使用Windows 7系统，桌面分辨率1920*1080，并没有在其他系统或分辨率测试过兼容性。

## 更新记录

2018年1月13日，上传了初始版本。

2018年2月11日，强化了拒绝悬赏的函数。

## 免责声明

网易，阴阳师，是网易公司的商标。 http://yys.163.com

按键精灵，是按键精灵公司的商标。 http://www.anjian.com

<!-- 根据 [GPLv3](https://www.gnu.org/licenses/gpl-3.0.html) 开源协议，本人不对该脚本负任何责任。-->

## 协议 (License)

该源代码使用了 [GPLv3](https://www.gnu.org/licenses/gpl-3.0.html) 开源协议。

This project is licensed under the [GPLv3](https://www.gnu.org/licenses/gpl-3.0.html) license.

