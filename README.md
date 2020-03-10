# intro
一些私人项目的介绍

## [epidemic](https://github.com/hanbaowang/epidemic)

node实现的疫情爬虫，爬取卫健委，主要技术栈
- request 实现页面爬取
- cheerio 实现页面解析
- nestjs 实现订阅接口
- redis 实现数据存储

## [bilibili-video-sync](https://github.com/hanbaowang/bilibili-video-sync)

chrome插件，实现bilibili用户同步看番/观看视频。用户可以在生成随机字符串，并发给朋友进行房间匹配，从而确定同步的对象。插件状态转移使用自行实现的简易状态机，数据同步使用基于websocket的deepstream。

## [logViewer](https://github.com/hanbaowang/LogViewer/tree/dev)

此处仅为不完全版本，供公司内部日志合并、展示使用。
golang, ssh取得服务器文件, 根据日志时间戳k路合并。
