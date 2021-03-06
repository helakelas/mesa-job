## 项目介绍
提供基于opentsdb的监控告警服务.服务于Mesa实时流服务

## 技术架构
opentsdb\quartz\Jetty

## 使用方式
- 通过http接口方式,进行任务管理(启动\暂停\删除\重启)
- milestone
  - 第一阶段 所有任务都保存在内存中,配置文件先单独维护
    - 20171026 Done
    - 维护的监控任务在 doc/metrics 目录中
  - 第二阶段 所有任务都保存在本地目录中,守护线程定时加载
  - 第三阶段 分布式


## 配置文件
[参见配置参数文档](how-to-use.md)

## 发布方式
[参见发布配置文档](how-to-publish.md)

## 业务监控配置
[参见监控文档](configured-metrics.md)

## 项目文档
项目文档使用 [`MkDocs(点击前往)`](how-to-use-mkdocs.md) ，依据文档配置文件 `mkdocs.yml` 可以比较方便的生成静态文档。


