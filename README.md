# wechat-jssdk-ts
微信JSSDK TypeScript版本

## 注意
本仓库只将微信官方的sdk下载到仓库中，并加上了TS的描述文件。

没有做其他任何改动

## 版本号说明
本仓库版本号构成

``
1.4.0-1.0.0-dev.0
``

一共分为四段段:

最后两段在正式包将不存在

第一段为wechat官方版本号，即`https://res.wx.qq.com/open/js/jweixin-1.4.0.js`URL中的1.4.0

第二段为本仓库的版本号，用于区分bug修复等等

第三段为版本状态，正式版本不存在。`dev,beta`为非正式版。一般不建议用于生产环境。

最后一个`.x`是当前`dev,beta`版本的第几个版本。一般用用于非正式版修复bug所用
