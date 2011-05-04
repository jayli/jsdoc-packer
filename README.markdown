# JSDOC 辅助脚本

jsdoc 生成js文档的辅助脚本，解决生成文档乱码问题，for linux only

- Created by [拔赤](http://jayli.github.com)
- License: [http://www.opensource.org/licenses/mit-license.php](http://www.opensource.org/licenses/mit-license.php)

## 准备 jsdoc-toolkit

- 下载并解压缩 [http://code.google.com/p/jsdoc-toolkit/downloads/list](http://code.google.com/p/jsdoc-toolkit/downloads/list)
- 拷贝 jsdoc-toolkit 目录到 /usr/local/lib/ 中

## 安装脚本 jsdoc

- 拷贝 [jsdoc](https://github.com/jayli/jsdoc-packer/raw/master/jsdoc) 脚本到 /usr/bin/ 中，并附权限
	
	sudo chmod 777 /usr/bin/jsdoc

## 脚本执行

运行

	jsdoc [项目源码目录] [目标目录]
