
1.使用命令`system.plugins`{{execute}} 来查看插件列表

2.使用命令 use + plugin 可以使用指定插件，如通过 ` system.use perf@LINUX`{{execute}} 来使用插件Perf

3.Perf是Perfma开发的一款Linux性能分析工具。
Linux性能计数器是一个新的基于内核的子系统，它提供一个性能分析框架，包含CPU、PMU(Performance Monitoring Unit)、tracepoint等功能。
通过Perf，应用程序可以利用PMU、tracepoint和内核中的计数器来进行性能统计。它不但可以分析指定应用程序的性能问题，也可以用来分析内核的性能问题，从而全面理解应用程序中的性能瓶颈。