# test_case_lts
lts分布式调度

LTS(light-task-scheduler)主要用于解决分布式任务调度问题，支持实时任务，定时任务和Cron任务。有较好的伸缩性，扩展性，健壮稳定性而被多家公司使用。<br>
1. 支持分布式，解决多点故障，支持动态扩容，容错重试等<br>
2. Spring扩展支持，Spring Quartz Cron任务的无缝接入支持<br>
3. 节点监控支持，任务执行监控支持，JVM监控支持<br>
4. 后台运维操作支持, 可以动态提交，更改，停止 任务<br>
<br>

本项目是从官网例子中摘选出springboot的集成方式，依赖zookeeper、mysql。
