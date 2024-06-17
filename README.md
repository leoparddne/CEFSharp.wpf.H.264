使用默认的cefsharp播放视频是无法播放的，因为cefsharp默认是不支持H.264编码的
![](https://img2018.cnblogs.com/blog/944369/202001/944369-20200117142901840-531157836.png)

chrome默认支持H.264
![](https://img2018.cnblogs.com/blog/944369/202001/944369-20200117144655905-204189656.png)

CEF默认不支持
![](https://img2018.cnblogs.com/blog/944369/202001/944369-20200117144925447-1532328516.png)

测试站点[http://html5test.com/](http://html5test.com/)

[下载所有的package](https://github.com/leoparddne/CEFSharp.wpf.H.264.git)


1. 首先nuget安装cefsharp for wpf 63.0.3
2. 用下载得到的【cef.redist.x64.3.3239.1723】、【cef.redist.x86.3.3239.1723】两个文件夹
替换原本项目目录中的对应文件(***工程目录下package目录中对应的文件夹***)即可

[测试项目](https://www.cnblogs.com/ives/p/cefh264.html)
可在此业务底部测试项目链接中获取(网站存在下载鉴权,直链容易失效)
