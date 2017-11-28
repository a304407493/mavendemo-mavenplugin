# mavendemo-spring
1.基于https://github.com/a304407493/mavendemo-pluginsql.git 创建maven骨架的spring项目<br/>
2.支持servlet2.3：<br/>
	增加jetty9插件和tomcat插件（没有日志）<br/>
		2.1.jetty9可以正常启动(webapp未生效，shutdown未生效)<br/>
		2.2.tomcat8无法正常启动(全部未生效)<br/>
		2.3.配置slf4j<br/>
		2.4.增加maven的sql插件<br/>
			执行方式：<br/>
				2.4.1.在mysql中创建yourdb的数据库<br/>
				2.4.2.执行命令mvn test（sql:execute不起作用）<br/>
				注：2.4.2.1.记得修改pom.xml的配置文件 2.4.2.2.创建yourdb的数据库<br/>
		2.5.增加mybatis<br/>
		2.6.spring3+调度任务quartz<br/>
		2.7.spring本身的调度任务<br/>
		2.8.quartz支持集群和多种方式配置<br/>
		2.9.支持druid，修改的druid本地数据库配置错误的地方<br/>
	增加sprinmvc<br/>
		引入webpath的方法<br/>
		java对象转js对象<br/>
		jquery、bootstrap的封装<br/>
		ajax的封装<br/>
		没有处理错误页面<br/>
	修复jetty9和tomcat插件<br/>
	jetty9和tomcat的命令<br/>
		jetty:run<br/>
		tomcat:run<br/>
