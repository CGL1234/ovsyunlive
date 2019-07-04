﻿# ovsyunlive
H5监控直播，微信直播，RTSP、RTMP转低延时h5直播，超低延时，监控直播系,支持http-flv,ws-flv,pc可以不用flash
针对H5在线抓娃娃，在线H5互动游戏，web监控,低延时解决方案

1、支持rtsp,rtmp,ws流互转直播。

2、支持rtsp，rtmp,H5低延时直播。

3、支持全平台H5网页（IOS,android,PC）低延时直播，可以到1秒内，最快0.2秒。 

4、支持IOS，微信自动直播播放。 

5、支持 微信内嵌入页技术，可以不全屏播放。 

4、动态拉流，更省流量，有人观看动态拉流，无人观看自动停流

5、支持rtmp的cdn云转发。

6、支持本地，云服务器多重部署（如本地监控可以本地部署一套拉流rtsp拉转推rtmp远程云，云服务器部署一套接收）。

测试，新绿色版直接git下载 https://codeload.github.com/ccallcn/ovsyunlive/zip/2.92

对延时要求较高，演示版不满足需要的，可以在线H5测试联系 QQ:1410919373      QQ群:108712418

启动：

1、双击运行，start.bat

2、网页打开http://127.0.0.1:10008/ 用户：admin 密码：admin

3、推流列表，添加拉流（支持rtmp,rtsp,监控摄像头） 目标本地地址：rtmp://127.0.0.1:1937/live/流id  

4、也可以直接用推流工具推流：rtmp://127.0.0.1:1937/live/流id

rtmp播放：rtmp://127.0.0.1:1937/live/流id

flv播放: http://IP:8000/live/流id.flv

ws-flv播放: ws://IP:8000/live/流id.flv

H5低延时播放: ovplay://IP:8801/live/流id

H5低码流播放: ovplay2://IP:8802/live/流id

5、ovplay播放器地址 http://127.0.0.1:10008/ovplay/ 配置播放

6、ovplay2更低码流播放器地址 http://127.0.0.1:10008/ovplay2/ 配置播放

停止：
1、运行，stop.bat

<p align="center"><img src="https://github.com/ccallcn/ovsyunlive/raw/master/TIM截图20190519124506.png" /></p>
<p align="center"><img src="https://github.com/ccallcn/ovsyunlive/raw/master/TIM截图20190519120437.png" /></p>
<p align="center"><img src="https://github.com/ccallcn/ovsyunlive/raw/master/TIM截图20190519120755.png" /></p>
<p align="center"><img src="https://github.com/ccallcn/ovsyunlive/raw/master/TIM截图20190519120849.png" /></p>
<p align="center"><img src="https://github.com/ccallcn/ovsyunlive/raw/master/TIM截图20190424172015.png" /></p>
<p align="center"><img src="https://github.com/ccallcn/ovsyunlive/raw/master/TIM截图20190519120935.png" /></p>
