

####一. 使用方法
在终端中调用以下代码,ipa母包路径作为sh文件运行参数。

	/Users/xxxx/new/autoIPA.sh "yyyy/zzzz/demo.ipa"
	
distDir目录中就是打好的所有的IPA包。

####二. 已有脚本的问题及本次改进
1. 在程序中使用plist文件存储所有渠道数据及当前渠道数据,渠道信息管理方便。plist是格式化信息的存储类型,查看、编辑、读取信息比较方便。已有脚本通过sourceid.dat和data.dat文件存放渠道信息。
2. 已有脚本需要每次修改sh文件中参数，新脚本直接从ipa母包中读取程序基本信息打包。
3. 通用性好,任何项目无需修改即可使用(程序必须使用指定格式的plist文件存储渠道信息)。

####三. 参考链接(已有脚本)
* [iOS自动化的打渠道包解决方案](http://mobile.51cto.com/hot-439106.htm)
* [ios自动化打包 教程（一）](http://blog.sina.com.cn/s/blog_7c8dc2d50101a52r.html)
* [ios自动化打包 教程（二）](http://blog.sina.com.cn/s/blog_7c8dc2d50101a53f.html)
* [IOS开发：自动化打包](http://blog.csdn.net/daiyelang/article/details/8641221)
