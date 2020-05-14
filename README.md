### xxl-job使用
#### 文档相关
- 参考文档：https://www.cnblogs.com/lwcode6/p/11340296.html
- 官方文档：https://www.xuxueli.com/xxl-job/

初一看，还挺复杂，但是仔细了解之后，不是很负责。
补充步骤：
### 配置调度中心
- 导入SQL文件。
    -  source /Users/mfw/IdeaProjects/xxl-job/doc/db/tables_xxl_job.sql
- 修改xxx-job-admin项目的数据库密码。
	-  xxl-job-admin/src/main/resources/application.properties
- 修改xxx-job-admin项目日志写入文件地址。
	-	xxl-job-admin/src/main/resources/logback.xml
- 访问地址：http://localhost:8080/xxl-job-admin/
### 配置部署执行器项目
- 修改xxx-job-admin项目的数据库密码。
	-	xxl-job-executor-samples/xxl-job-executor-sample-springboot/src/main/resources/application.properties
- 修改xxx-job-admin项目日志写入文件地址。
	-	xxl-job-executor-samples/xxl-job-executor-sample-springboot/src/main/resources/logback.xml

