# 简介
九价HPV疫苗太难抢了，每次手动抢根本抢不到，闲时考虑能不能写个程序来抢，本脚本由此诞生。

本程序完全模拟人的点击操作，并非利用cookie什么的来抢，只是在点击抢购的按钮的时候用程序来点击，程序总比我的手指快吧。
## 使用设备
本程序仅适用于Windows+Android设备
## 环境：
```
pip3 install uiautomator2
```
## 使用方式
1. 首先你需要在“约秒”小程序-我的-家庭成员管理 里面填写好你的个人信息
2. 用数据线将手机连接到电脑，在cmd执行adb devices（前提是你装好了ddb），出现你的设备就成功了
3. 继续运行命令 python -m uiautomator2 init ，会自动在你手机上安装一个 ATX的程序
4. 在开抢前3-5分钟运行本程序
