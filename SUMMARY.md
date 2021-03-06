# Summary

* [前言](README.md)
* [修订记录](revision-record.md)
* [如何贡献](how-to-contribute.md)
* [Prometheus 简介](introduction/README.md)
    * [Prometheus 是什么？](introduction/what.md)
    * [为什么选择 Prometheus？](introduction/why.md)
* [Prometheus 安装](install/README.md)
  * [二进制包安装](install/binary.md)
  * [Docker 安装](install/docker.md)
* [基础概念](concepts/README.md)
  * [数据模型](concepts/data-model.md)
  * [Metric types](concepts/metric-types.md)
  * [作业与实例](concepts/jobs-and-instances.md)
* [PromQL](promql/README.md)
  * [PromQL 基本使用](promql/summary.md)
  * [与 SQL 对比](promql/sql.md)
* [数据可视化](visualiztion/README.md)
  * [Web Console](visualiztion/console.md)
  * [Grafana](visualiztion/grafana.md)
* [Prometheus 配置](configuration/README.md)
  * [全局配置](configuration/global.md)
  * [告警配置](configuration/alerting.md)
  * [规则配置](configuration/rule_files.md)
  * [数据拉取配置](configuration/scrape_configs.md)
  * [远程可写存储](configuration/remote_write.md)
  * [远程可读存储](configuration/remote_read.md)
  * [服务发现](configuration/server_discovery.md)
  * [配置样例](configuration/demo.md)
* [Exporter](exporter/README.md)
  * [文本格式](exporter/text.md)
  * [Sample Exporter](exporter/sample.md)
  * [Node Exporter 安装使用](exporter/nodeexporter.md)
  * [Node Exporter 常用查询](exporter/nodeexporter_query.md)
  * [Node Exporter Grafana 模版](exporter/nodeexporter_grafana_template.md)
  * [其他 Exporter 介绍](exporter/other.md)
* [Pushgateway](pushgateway/README.md)
    * [Pushgateway 是什么？](pushgateway/why.md)
    * [如何使用 Pushgateway? ](pushgateway/how.md)  
* [数据存储](store/README.md)
    * [Local Store](store/local.md)
    * [Remote Store](store/remote.md)
* [Rule](rule/README.md)
    * [如何配置](rule/config.md)
    * [Rule 触发逻辑](rule/what.md)  
* [Alertmanager](alertmanager/README.md)
    * [Alertmanager 是什么？](alertmanager/what.md)
    * [配置详情](alertmanager/config.md)  
    * [通过 Email 接收告警](alertmanager/email.md)  
    * [通过企业微信接收告警](alertmanager/wechat.md)
    * [通过 Slack 接收告警](alertmanager/slack.md)  
    * [通过 Webhook 接收告警](alertmanager/webhooks.md)  
    * [其他告警接收方案](alertmanager/others.md)
* [主机监控完整示例](demo/README.md)
    * [Target 配置](demo/target.md)
    * [Rule 配置](demo/rule.md)
    * [Alertmanager 配置](demo/alertmanager.md)
    * [Grafana 集成](demo/grafana.md)
* [Prometheus 工具](tools/README.md)
    * [Promu 介绍和使用](tools/promu.md)
    * [Client SDK](tools/client.md)
* [Prometheus 性能调优](optimize/README.md)
    * [通过 Metrics 查看 Prometheus 运行状态](optimize/status.md)
    * [通过日志分析 Prometheus 运行状态](optimize/logger.md)
    * [启动参数详解](optimize/config.md)
* [Prometheus 与容器](container/README.md)
    * [Docker](container/docker.md)
    * [Kubernetes](container/k8s.md)
* [Prometheus 常见服务监控](service/README.md)
    * [Nginx](service/nginx.md)
    * [Memcached](service/memcached.md)
    * [MongoDB](service/mongodb.md)
    * [MySQL](service/mysql.md)
    * [Redis](service/redis.md)
* [Prometheus 与 DevOps](devops/README.md)
    * [从 0 开发一个 exporter](devops/exporter.md)
    * [使用 Webhooks 开发一个 alert receiver](devops/receiver.md)
* [高可用方案探讨](ha/README.md)
    * [Prometheus Server 的高可靠](ha/prometheus.md)
    * [AlertManager 的高可靠](ha/alertmanger.md)
* [v2.x 迁移注意](v2.0/README.md)
    * [新功能](v2.0/feature.md)
    * [新存储架构](v2.0/store.md)
    * [Rule 新配置](v2.0/rule.md)
* [常见问题收录](qa/README.md)
    * [如何热加载新配置？](qa/hotreload.md)
    * [为什么重启 Prometheus 过后，数据无法查询？](qa/hotreload.md)
    * [如何删除 Pushgateway 的数据？](qa/pushgateway.md)
    * [为什么内存使用这么高？](qa/memory.md)
    * [为什么有数据丢失？](qa/losedata.md)
    * [Prometheus 如何通过认证后拉取数据？](qa/auth.md)
    * [监控 JVM](qa/jvm.md)
    * [监控 Ruby On Rails 应用](qa/rails.md)
