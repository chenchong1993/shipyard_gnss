# shipyard_gnss
使用方法：
首先按照网上的方法安装英文版shipyard,大致分为以下步骤：
	1.拉取必要镜像
	2.下载安装脚本-deploy
	3.执行安装
然后把docker shipyard/shipyard:latest容器的static下的index.html和app文件夹用本项目的index.html和app替换掉.命令：
	docker cp index.html 15b7fb50ab57:/static/
	docker cp app 15b7fb50ab57:/static/
最后，刷新网页即可。

自定义修改：
/static/index.html---可以把标题修改为自己想要的名字
/static/app/layout/dashboard.html---可以把标题修改为自己想要的名字
/static/app/login/login.html---可以把标题,和下面的软件所有权修改为自己想要

本项目源于git项目：GeekCloud-Team/shipyard_zh
地址：https://github.com/GeekCloud-Team/shipyard_zh.git