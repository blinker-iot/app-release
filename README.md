# app-release  
## 应用商店安装  
[Google play安装](https://play.google.com/store/apps/details?id=iot.clz.me)  
[app store安装](https://itunes.apple.com/cn/app/id1357907814)  
[github下载](https://github.com/blinker-iot/app-release/releases)  
[bug提交](https://www.arduino.cn/thread-81133-1-1.html)  
## 更新记录  
**以下版本号以android版为准，ios版本号不同**  
**2.0.4-beta**[下载](https://github.com/blinker-iot/app-release/releases/download/2.0.4-beta/blinker-2.0.4-beta.apk)  
重新开放了场景控制功能，可以通过添加场景按键，一键控制多个设备。  
[使用方法](https://doc.blinker.app/?file=005-App%E4%BD%BF%E7%94%A8/05-%E5%9C%BA%E6%99%AF%E6%8E%A7%E5%88%B6)  
<br>
**2.0.3**[下载](https://github.com/blinker-iot/app-release/releases/download/2.0.3-beta/blinker-2.0.3-beta.apk)  
0.现在MQTT在局域网中会自动切换到局域网通信，局域网通信没有发送频率限制  
1.添加首页deviceblock开关返回声音震动  
2.添加定时同步提示  
3.添加不在线无法使用定时提示  
4.修复了个别bug  
<br>
**2.0.2**[下载](https://github.com/blinker-iot/app-release/releases/download/2.0.2/blinker-2.0.2.apk)  
== 2.x版本app需配合blinker lib 2.x版本使用 ==  
1.MQTT数据合并发送，现在是MQTT接入，所有动作都会延迟300ms发送，300ms内如果触发其他动作，数据将会合并成一条消息发送  
2.在设备控制面板页面，MQTT连接的设备每59秒会进行一次状态查询，WiFi连接的设备每29秒会进行一次状态查询  
3.意外断网后，可以自动重连了  
4.修复设备拖拽排序无法保存的bug  
5.修复其他bug  
<br>
**2.0.1**[下载](https://github.com/blinker-iot/app-release/releases/download/2.0.1/blinker-2.0.1.apk)  
== 2.x版本app需配合blinker lib 2.x版本使用 ==  
1.新UI  
2.新的DIY布局器  
3.添加了定时功能  
4.优化诸多细节  
5.修复诸多bug  
<br>
**2.0.1-beta**[下载](https://github.com/blinker-iot/app-release/releases/download/2.0.1-beta/blinker2.0.1-beta.apk)  
== 2.x版本app需配合blinker lib 2.x版本使用 ==  
1.重制UI  
2.重写了界面编辑器  
3.修复若干小问题  
<br>
**1.0.2**[下载](https://github.com/blinker-iot/app-release/releases/download/1.0.2/blinker-1.0.2.apk)  
更新内容：  
1.添加场景开关功能  
2.添加开发工具>esptouch功能  
3.优化若干细节  
4.修复若干bug  
<br>
**1.0.1**[下载](https://github.com/blinker-iot/app-release/releases/download/1.0.1-beta/blinker-1.0.1-beta.apk)  
更新内容：  
1.新增场景按键，可以一次控制多个设备（点击app首页右上角的三点，即可看到）  
2.新增设备拖拽排序，现在你可以改变设备的排列顺序  
3.语音按钮位置调到tab栏  
4.添加界面编辑未保存退出的提示  
5.优化了其他诸多细节  
<br>
**0.9.7**[下载](https://github.com/blinker-iot/app-release/releases/download/0.9.7/blinker-0.9.7.apk)  
1.添加语音控制功能  
2.优化WiFi接入，搜索设备、连接设备的速度  
3.优化在魅族、Vivo等手机上的显示  
4.优化蓝牙数据传输  
<br>
**0.9.6**  
1.添加设备推送消息通知功能；  
2.支持中文消息内容；  
3.优化颜色选择和滑动选择组件；  
4.部分组件支持了反向控制；  
<br>
**0.9.5**  
支持MQTT接入；  


## 项目鸣谢  
项目当前使用开发框架：  
angular5、cordova8、ionic3  
本项目使用或曾经使用过如下项目资源：  
cordova-plugin-ble-central  
cordova-plugin-code-push  
cordovanetworkmanager  
cordova-plugin-smartconfig  
cordova-plugin-bdasr  
cordova-plugin-shortcuts-android  
cordova-plugin-zeroconf  
jpush-phonegap-plugin  
cordova-android-support-gradle-release  
angular-gauge  
angular-gridster2  
cropperjs  
echarts  
ng-dynamic-component  
sortablejs  
chart.js  
android-versions  



