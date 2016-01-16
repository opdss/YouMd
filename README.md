# YouMd
基于 [Editor.md](https://github.com/pandao/editor.md) 的MarkDown在线书写工具，很方便在本地/局域网/服务器快速运行，即时保存，在线管理

# 特性
* 快速便捷地运行，拿来即用
* 即时保存到本地客户端
* 在线管理和查阅

# 使用
运行：
python server.py

访问：
首页 http://localhost:8081/

编辑器 http://localhost:8081/new


# 说明
发布保存的文档默认以.md存放在raw/entry/目录下

可配置的地方如下：
* config.py 配置一些常量、路径等
* templates/layout/ 配置站点头部、尾部及主菜单


# 定位
拿来即用的MarkDown编辑器；

如果你愿意它会是一个不错的轻博客系统（纯文档化）；

如果你想到了，它也可以是便捷的团队文档wiki系统

Screenshots
========
![info](https://github.com/JoneXiong/YouMd/raw/master/static/img/editor.png)

![info](https://github.com/JoneXiong/YouMd/raw/master/static/img/blog.jpg)

![info](https://github.com/JoneXiong/YouMd/raw/master/static/img/publish.jpg)

![data](https://github.com/JoneXiong/YouMd/raw/master/static/img/update.jpg)
