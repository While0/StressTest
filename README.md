# StressTest
Loadrunner虽好，但，它不是免费的，使用它就是行走在某种边缘；而且动不动就2G的安装包，实在难于下载和安装。

为何不用python实现一个性能测试的脚本呢？ 
从监控主机的CPU、内存、网络和磁盘开始， 
到使用unittest的单元测试用例组建测试场景。 
再到发起并发测试，获得监控数据； 
最后生成性能表现图，从而分析应用的表现。 
python都可以做到。 

使用到了sar，iostat和shell脚本进行监控 。
使用了matplotlib，numpy,pylot等画图分析。
