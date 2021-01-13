
process在XPocket里代表解决某个问题的经验沉淀，也可以理解为把多个步骤的命令组装起来，然后以别名的方式记录，举个简单的例子，
比如我们需要找出服务器上所有的java进程，通常我们需要执行 ps -ef | grep java，但是在XPocket里我们可以先把这段指令保存起来，
如`proc_save searchJavaProcess "ps -ef | grep java"`{{execute}}。

这样我们就完成了命令的简化工作，通过`proc_list`{{execute}}可以列出所有可执行别名列表。

最后通过`proc_exec searchJavaProcess`{{execute}} 即可以达到ps -ef | grep java一样的效果。
