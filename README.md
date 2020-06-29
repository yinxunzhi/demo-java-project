# demo-java-project
根据个人的项目经验以及一些开源框架的整理出的项目结构，项目自底向上分为如下几个模块
- demo-deploy:用于存放发布脚本
- demo-config:放置项目的配置文件，比如spring配置文件，dubbo配置文件等
- demo-dependency：对外部系统调用的封装
- demo-dao:DAO层，包括DO,DAO,mapper配置文件等
- demo-service:业务处理层
- demo-api-impl:对外接口提供实现类
- demo-api:对外接口
- demo-web:启动类和Http接口访问
