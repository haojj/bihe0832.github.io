---
layout: post
title: 基于mdwiki使用Markdown实现的wiki
category: web前端
tags: mdwiki 酷炫 wiki markdown bootstrap
description: MSDK团队早期尝试过使用wiki，然而由于wiki的语法太过复杂，编辑的时间成本很高，所以最终还是没能坚持。但是文档online化总要解决，不然上面的问题会一直存在。为了让伟大的开发哥哥们不受困于wiki，最后在github终于找到了神器。mdwiki一个基于bootstrap的，使用markdown编辑内容的js wiki框架。
---
## 写在前面

MSDK做了这么久，被开发商嗤之以鼻最多的问题之一就是文档。问题的原因比较多，主要是三个方面：

1. MSDK没有完整的线上文档，所有的文档都是跟随版本包。
2. MSDK同时外发版本太多
3. MSDK的版本文档使用word编写，不同版本文档不易比对。

由于以上的问题，经常出现游戏更新版本以后没有同步使用新版本的文档，无法同步更新我们已经修正的文档错误，或者由于文档比对太过麻烦和版本太多，开发修改文档错误以后比较难同步修改到其余版本。

为了解决这个问题，MSDK团队早期尝试过使用wiki，然而由于wiki的语法太过复杂，编辑的时间成本很高，所以最终还是没能坚持。但是文档online化总要解决，不然上面的问题会一直存在。为了让伟大的开发哥哥们不受困于wiki，最后在github终于找到了神器。mdwiki一个基于bootstrap的，使用markdown编辑内容的js wiki框架。

## 源码地址：
[https://github.com/bihe0832/MSDK-wiki/](https://github.com/bihe0832/MSDK-wiki/)
## 目录结构

- **android：Android Wiki相关文档**

	- navigation.md：Android Wiki 菜单配置文件
	- config.json：Android Wiki 风格配置
	- *.md：Android 各模块文档
	- *.jpg：Android 文档中用到的图片

- **CSS：wiki页面相关的css**

- **font：wiki页面使用到的特殊字体**

- **ios：IOS Wiki相关文档**

	- navigation.md：IOS Wiki 菜单配置文件
	- config.json：IOS Wiki 风格配置
	- *.md：IOS 各模块文档
	- *.jpg：IOS 文档中用到的图片	


- **js：wiki页面相关的js**

- **router：Router Wiki相关文档**

	- navigation.md：Router Wiki 菜单配置文件
	- config.json：Router Wiki 风格配置
	- *.md：Router 各模块文档
	- *.jpg：Router 文档中用到的图片

- **upload：wiki文档上传工具**

- **MSDK文档指引.html：MSDK文档相关链接**

## WIKI链接

- **Wiki 地址：**

	- Android Wiki：http://wiki.dev.4g.qq.com/v2/android/index.html
	- IOS Wiki：http://wiki.dev.4g.qq.com/v2/ios/index.html
	- 后台 Wiki：http://wiki.dev.4g.qq.com/v2/router/index.html

- **MSDK版本历史：**

	- Android 版本历史：http://wiki.dev.4g.qq.com/v2/android/index.html#!version.md
	- IOS 版本历史：http://wiki.dev.4g.qq.com/v2/ios/index.html#!version.md
	
## MDWiki相关介绍：

####github地址：[https://github.com/Dynalon/mdwiki](https://github.com/Dynalon/mdwiki)

#####官网：[http://www.mdwiki.info](http://www.mdwiki.info)

####使用指引：参见github地址