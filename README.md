# clash_debug_note

linux试着装了个clash
然后遇到了如下问题：
解压出来的应用程序不可执行
后来发现是
在运行配置文件的时候解压方法错误，体现为日期为1970年

.tar.gz的文件，我之前用的是tar -zxvf yourfile.tar.gz解压
但是实际上要用gunzip yourfile.tar.gz解压
呃……
