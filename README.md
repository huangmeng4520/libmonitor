libmonitor
=======================
libmonitor is a c/c++ package that you can easily report metrics to shm.
***
libmonitor是一个c/c++库，用于业务程序上报属性监控量，如请求量、失败量、超时量，使用率等。属性监控值上报到本地的共享内存，所以执行效率非常高。
[moni-exporter](https://github.com/jimdn/moni-exporter)会读取共享内存里面的值，并提供http接口供[prometheus](https://github.com/prometheus/prometheus)采集

<br />
以下提供go版本的属性监控API库：

* [gomonitor](https://github.com/jimdn/gomonitor)

<br />
结合以下组件和脚本，即可搭建起一套完整的监控和告警系统：

* [prometheus](https://github.com/prometheus/prometheus)
* [grafana](https://github.com/grafana/grafana)
* [moni-exporter](https://github.com/jimdn/moni-exporter)
* [moni-alert](https://github.com/jimdn/moni-alert)
* [moni-dashboard-generator](https://github.com/jimdn/moni-dashboard-generator)

<br />
详细可参考如下文章：

* [xxx文章](https://github.com/jimdn/moni-dashboard-generator)
