# WordPress版微信小程序

![wordpress微信小程序](https://www.watch-life.net/images/2017/08/weixinapp220.png) 

# 功能清单：

1.缩略图的方式显示文章列表（首页，分类文章），包括显示文章分类和发布时间，加载分页。

2.在首页用轮播方式显示置顶文章。

3.显示文章分类（专题），包括显示分类的封面图片。

4.显示文章内容页，包括文章站内链接跳转，站外链接复制到剪切板，显示猜你喜欢的相关文章。

5.显示文章评论，提交评论和回复评论，加载评论分页，显示微信用户评论者的头像。

6.显示热点文章。

7.显示wordpress“页面”类文字（关于页面）。

8.对文章内容的全文搜索。

9.小程序页面的分享和转发。

10.WordPress 插件的配套功能。

# 技术支持网站：https://www.watch-life.net(该域名从2017年8月29日开始域名备案，暂时无法访问)

# 技术支持的网站暂时请访问：https://www.zhaen.com (以下访问链接请自行修改域名)

# 小程序配套wordpress插件：

本小程序需要配合wordpress插件wp-rest-api-for-app，才能完整使用，插件下载地址： https://github.com/iamxjb/wp-rest-api-for-app

# 开源协议：MIT

# 技术支持微信：iamxjb

![iamxjb](https://www.watch-life.net/images/iamxjbweixin.jpg) 

# 程序开发系列文章

<a href="https://www.watch-life.net/wordpress/weixin-connect-wordpress.html" target="_blank">1.用微信小程序连接WordPress网站</a>

<a href="http://WordPress版微信小程序1.5版本发布" target="_blank">2.WordPress版微信小程序1.5版本发布</a>

<a href="https://www.watch-life.net/wordpress/wordpress-weixin-2.html" target="_blank">3.WordPress版微信小程序2.0版本发布</a>

<a href="https://www.watch-life.net/wordpress/wordpress-rest-api-weixin-weapp.html" target="_blank">4.利用WordPress REST API 开发微信小程序从入门到放弃</a>

<a href="https://www.watch-life.net/wechat/wordpress-weixin-2-1-5.html" target="_blank">5.WordPress版微信小程序2.1.5版本发布</a>

<a href="https://www.watch-life.net/wordpress/wordpress-weixin-2-1-8.html" target="_blank">5.WordPress版微信小程序2.1.8版本发布</a>

<a href="https://www.watch-life.net/wordpress/wordpress-weixin-2-2-0.html" target="_blank">5.WordPress版微信小程序2.2.0版本发布</a>


# 讨论微信群：

由于微信群超过100人，无法再扫描二维码加入。如果你想加入，请先加我的微信：iamxjb ，我拉你入群。

# 开源声明：

1、本程序html转wxml的解析采用的是https://github.com/icindy/wxParse
2、专题页面及浏览记录页面的设计思路参考 https://devework.com/  网站的小程序

在此对上述提供开源及创意表示致谢。



# 捐赠赞赏：请微信扫描以下二维码。感谢您对我的支持，您的支持是我前进的动力

![weixinpay](https://www.watch-life.net/images/2017/06/weixinpay150.png) 

# 更新历史：

## 2017年8月17日
1.增加站内链接。

2.增加猜你喜欢功能。

3.增加热点文章功能。

4、取消浏览记录功能。

## 2017年7月29日

1.完善文章的评论，按评论时间对一级评论按时间先后显示，最新发表的显示在最上面。

2.以嵌套的方式显示评论和回复，最多显示5层嵌套。

3.增加评论的回复功能，可以针对4级评论（回复）进行回复。

4.文章内容页加入一直没有引入的wxParse.wxss文件（弥补愚蠢的错误）。

## 2017年7月15日

1.完善首页列表的缩略。调整为150*150的小图，需要配合wp-rest-api-for-app插件.

2.去除侧滑菜单。增加专题分类，并完善搜索。

3.完善评论及显示。

4.优化程序性能，整理wxss，让程序代码更易懂和美观.

5.修复获取微信头像bug，当头像如果是https地址的话，不强制转换成https。

6.修复没有置顶文章，下拉刷新不显示列表的bug。

7.为评论增加分页，提供分页刷新的功能。


## 日期：2017年6月6日

内容：

1.调整列表页的显示方式。

2.增加搜索。

3.首页增加轮播图片和缩略图。

4.增加文章评论

5.增加小程序分享

升级的详细说明见： https://www.watch-life.net/wordpress/wordpress-weixin-2-html.html


## 日期：2017年5月15日

内容：

1.在主页面，加入浮动按钮，用来打开侧滑导航菜单。

2.增加侧滑导航菜单，菜单上包括页面及文章分类.侧滑菜单代码参考WechatSmallApps（https://github.com/jkgeekJack/WechatSmallApps）的代码修改。

3.优化下拉刷新数据（分页）的性能。

4.文章列表页添加发布时间。

5.升级最新的微信小程序富文本解析组件wxParse（https://github.com/icindy/wxParse）

升级的详细说明见：https://www.watch-life.net/wordpress/wordpress-weixin-1-5.html


