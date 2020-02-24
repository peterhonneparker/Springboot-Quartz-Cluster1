# 本案例实现SpringBoot整合quartz实现定时任务(集群版)  
cron表达式配置在application.yml文件中  
注：运行前需要执行quartz.sql  

本项目基于其他项目,更改了某些配置文件,目前简单测试发现的问题是:Trigger的misfire策略设置失败

TODO: 执行日志记录功能
动态修改数据库中Cron表达式
