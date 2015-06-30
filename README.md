# go-post-scatter
	go http post echarts scatter 
	golang 并发测试 http post 并使用echarts输出表表统计运行时间
##目录介绍
	运行Client生成并发报表 分析基本每次连接执行时间
	out 输出目录
	config 配置目录

	golang代码修改
	修改config文件夹里面的config/output.html里面需要替换的内容 用%s代替


##修改扩展
	由于连接的是自己的golang服务器，
	需要修改链接的服务器地址，
	和修改代码里面http传输的内容修改才能实现
	修改getPostUploadResData方法
	修改postLoginTest登录测试
##测试scatter图链接

* [1000并发图](http://jixieshi999.github.io/go-post-scatter/1000-20150630_105032.html)
* [200并发图](http://jixieshi999.github.io/go-post-scatter/200-20150630_104709.html)


