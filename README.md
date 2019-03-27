![](https://i.imgur.com/dUvNgmd.jpg)  

# [Proxyee Down](https://pdown.org)
[![Author](https://img.shields.io/badge/author-monkeyWie-red.svg?style=flat-square)](https://github.com/monkeyWie)
[![Contributors](https://img.shields.io/github/contributors/proxyee-down-org/proxyee-down.svg?style=flat-square)](https://github.com/proxyee-down-org/proxyee-down/graphs/contributors)
[![Stargazers](https://img.shields.io/github/stars/proxyee-down-org/proxyee-down.svg?style=flat-square)](https://github.com/proxyee-down-org/proxyee-down/stargazers)
[![Fork](https://img.shields.io/github/forks/proxyee-down-org/proxyee-down.svg?style=flat-square)](https://github.com/proxyee-down-org/proxyee-down/fork)
[![License](https://img.shields.io/github/license/proxyee-down-org/proxyee-down.svg?style=flat-square)](https://github.com/proxyee-down-org/proxyee-down/blob/master/LICENSE)

> Proxyee Down 是一款开源的免费 HTTP 高速下载器，底层使用`netty`开发，支持自定义 HTTP 请求下载且支持扩展功能，可以通过安装扩展实现特殊的下载需求。

## 使用教程

[点击查看教程](https://github.com/proxyee-down-org/proxyee-down/wiki/%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B)

## 交流群

1 群**11352304**、2 群**20236964**、3 群**20233754**、4 群**737991056**

## 开发

本项目后端主要使用 `java` + `spring` + `boot` + `netty`，前端使用 `vue.js` + `iview`

### 环境
![](https://img.shields.io/badge/JAVA-1.8%2B-brightgreen.svg) ![](https://img.shields.io/badge/maven-3.0%2B-brightgreen.svg) ![](https://img.shields.io/badge/node.js-8.0%2B-brightgreen.svg)

	oracle jdk 1.8+或 openjfx(openjdk默认不包含javafx包)

### 编译

```
git clone https://github.com/proxyee-down-org/proxyee-down.git
cd proxyee-down/front
#build html
npm install
npm run build
cd ../main
mvn clean package -Pprd
```

### 运行
```
java -jar proxyee-down-main.jar
```


windows下：



下载Proxyee-Down后，第一次启动，我们先在主界面上方找到【扩展管理】，然事先点击，点击后后我们会看到有两个扩展，然后我们下载并安装扩展，如下图:
<img class="aligncenter size-full wp-image-3167" alt="Proxyee-Down 3.4.0 百度网盘不限速下载神器，支持Win/Mac/Linux" src="https://ws3.sinaimg.cn/large/006ZzzVqgy1fzcpbtd6l8j30sg0hrwgp.jpg" width="1024" height="639" />
百度云下载的扩展一定要开启，要不然提取不了直链，全网嗅探的话开了的话只需pro在运转，下载东西都会跳转到pro下载，这个根据你自己的需求开！
<img class="aligncenter size-full wp-image-3168" alt="Proxyee-Down 3.4.0 百度网盘不限速下载神器，支持Win/Mac/Linux" src="https://ws4.sinaimg.cn/large/006ZzzVqgy1fzcpbthah7j30sg0hrabi.jpg" width="1024" height="639" />
扩展安装好了我们来试试百度云下载的扩展，在阅读器翻开一个百度云资源链接，你会发现多了这个按钮，如图:
<img class="aligncenter size-full wp-image-3169" alt="Proxyee-Down 3.4.0 百度网盘不限速下载神器，支持Win/Mac/Linux" src="https://ws1.sinaimg.cn/large/006ZzzVqgy1fzcpbtqw4cj30vo0hxwgk.jpg" width="1140" height="645" />
假设资源只需一个链接的话，我们就点击直链下载，就会推送链接到pro中止高速下载！假设资源链接里的一切资源加起来不逾越300兆，我们还可以选择紧缩链接下载！假设链接里的资源比较多也比较大，那麼我们就选择批量推送下载！
<img class="aligncenter size-full wp-image-3170" alt="Proxyee-Down 3.4.0 百度网盘不限速下载神器，支持Win/Mac/Linux" src="https://ws3.sinaimg.cn/large/006ZzzVqgy1fzcpbu4xdpj30vm0fjjtl.jpg" width="1138" height="559" />



成果: 假设下载了一会儿没网速了怎样办呢？



这个情况的话是下载的直链失效了，不要慌，且看我渐渐道来！遇到这种情况，我们不用删除资源，pro是支持更新下载链接的！假设我们下载的是单个资源，就去百度云那里再推送一遍资源直链中止下载，它会提示能否需求刷新链接，然后你选择对应的义务即可！
假设是批量下载的资源不动了怎样办呢？我们先看一下不动的资源的文件名，然后再在百度云里找到这个资源，重新推送这个资源的直链中止刷新链接！
<img class="aligncenter size-full wp-image-3171" alt="Proxyee-Down 3.4.0 百度网盘不限速下载神器，支持Win/Mac/Linux" src="https://ws4.sinaimg.cn/large/006ZzzVqgy1fzcpbue619j30sg0hrq46.jpg" width="1024" height="639" />



百度云下载的大约需求知道的就是这些:



下面我们来说说嗅探:
开启嗅探扩展的话需求开启全局代{过}{滤}理，这样可以会招致某些网站无法访问，在下载资源后封锁即可！
开启全局代{过}{滤}理后，我们就可以经过Pro高速下载支持多线程下载的资源了，这里要留意，不能下载城通网盘这类平台的普通链接的资源！
比方说用迅雷下载下图的这个直链资源有版权成果，而用阅读器下载又慢，用Pro下载就是很好的办法
<img class="aligncenter size-full wp-image-3172" alt="Proxyee-Down 3.4.0 百度网盘不限速下载神器，支持Win/Mac/Linux" src="https://ws3.sinaimg.cn/large/006ZzzVqgy1fzcpbujflpj30sg0hrgmo.jpg" width="1024" height="639" />

----------------------
原文：https://www.hezibuluo.com/proxyee-down-3.html
