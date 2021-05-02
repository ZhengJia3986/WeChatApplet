本项目来自B站教程视频,想看原视频请移步:https://www.bilibili.com/video/av40455083/
--
关于`font-awesome`的问题：
* `font-awesome`下载地址http://fontawesome.dashgame.com/  
* 下载后解压`css`文件后缀改名`wxss`
* 播放图标矢量图库亲测可用http://www.staticfile.org/  
* 搜索`font-awesome`里面有链接
```
代码链接格式
@font-face {
  font-family: FontAwesome;
  src: url(https://cdn.staticfile.org/font-awesome/4.7.0/css/font-awesome.css);
  src:
  url(https://cdn.staticfile.org/font-awesome/4.7.0/fonts/fontawesome-webfont.woff2) format(woff2), 
  url(https://cdn.staticfile.org/font-awesome/4.7.0/fonts/fontawesome-webfont.woff) format(woff), 
  url(https://cdn.staticfile.org/font-awesome/4.7.0/fonts/fontawesome-webfont.svg) format(svg),
  url(https://cdn.staticfile.org/font-awesome/4.7.0/fonts/fontawesome-webfont.eot) format(eot),
  url(https://cdn.staticfile.org/font-awesome/4.7.0/fonts/fontawesome-webfont.ttf) format(ttf);
  font-weight: normal;
  font-style: normal;
}
```
关于页面空白不显示问题：
* 是由于老师用的`easymock`接口不稳定，容易突然就挂了，经常性的`404 Not Found`
* 可以借鉴我项目里面的自己做的接口`url`地址，数据接口用的fastmock,如果挂了证明接口也过期了
* 我整理了几个目前还可以用的接口`url`放在下面可以借鉴一下,如果不行就自己做吧/doge
```
首页导航：
http://mock-api.com/mnEe4VnJ.mock/navList
https://mockapi.eolinker.com/7b7NMB9c75d613bc39c8f16e4e03a3d4a8f951750079dc5/navList
轮播图：
http://mock-api.com/mnEe4VnJ.mock/swiperList
https://mockapi.eolinker.com/7b7NMB9c75d613bc39c8f16e4e03a3d4a8f951750079dc5/swiperList
视频列表：
http://mock-api.com/mnEe4VnJ.mock/videoList
https://mockapi.eolinker.com/7b7NMB9c75d613bc39c8f16e4e03a3d4a8f951750079dc5/videoList
视频详情：
http://mock-api.com/mnEe4VnJ.mock/videoDetail
https://mockapi.eolinker.com/7b7NMB9c75d613bc39c8f16e4e03a3d4a8f951750079dc5/videoDetail
推荐视频：
http://mock-api.com/mnEe4VnJ.mock/otherList
https://mockapi.eolinker.com/7b7NMB9c75d613bc39c8f16e4e03a3d4a8f951750079dc5/otherList
评论列表：
http://mock-api.com/mnEe4VnJ.mock/commentList
https://mockapi.eolinker.com/7b7NMB9c75d613bc39c8f16e4e03a3d4a8f951750079dc5/commentList
```
其他的大概没什么问题了，附上两张运行截图：

![image](https://user-images.githubusercontent.com/62896788/116807803-c761f900-ab67-11eb-977a-33df3c8bbf81.png)
![image](https://user-images.githubusercontent.com/62896788/116807811-cdf07080-ab67-11eb-8438-4d6112d2d41a.png)

另外，老师视频中所用到的讲义是微信开放文档：
```
https://developers.weixin.qq.com/miniprogram/dev/framework/sitemap.html
```
