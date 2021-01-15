
1.使用命令`system.plugins`{{execute}} 来查看插件列表。

2.使用命令 use + pluginName@NAMESPACE 来使用插件，如`use jdb@JDK`{{execute}}。

3.使用`jdb -help`{{execute}} 获取jdb的详细使用帮助。
4.使用`jdb -classpath .:/root/simulator`{{execute}} 来启动一个jdb会话
5.使用`stop in XPocketDemo.systemOut`{{execute}} 在systemOut这个方法上设置一个断点
6.`run XPocketDemo`{{execute}}来启动XPocketDemo
7.`cont`{{execute}}来继续执行
8. 详细的jdb使用方法参见[jdb官方文档](https://docs.oracle.com/javase/8/docs/technotes/tools/windows/jdb.html)