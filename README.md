
1. 必要的条件
	- 日志格式清晰，包含
		- 时间
		- 日志等级
		- 日志代码的文件及行数
		- 线程id
		- 日志内容
	- 日志等级、日志文件名称、日志文件大小允许设置
	- 日志文件按大小和天数自动滚动
	- 性能达标，不拖累主程序的运行
2. 非必要的条件：
	- 不同的日志记录对应不同的日志文件
	- 跨平台
	- 提供动态语言（eg. lua）的日志接口
3. gtest 也用上
4. doxygen 格式也安排上