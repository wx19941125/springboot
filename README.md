## Welcome to springboot

	好处，内置tomcat;maven项目;开箱即用，无需XML配置;

	需要说明的是SpringBoot依赖的JDK版本为1.8及以上 （springboot配置Java与springboot配置maven）;

### idea 搭建springboot环境

	@responseBody注解的作用是将controller的方法返回的对象通过适当的转换器转换为指定的格式之后，写入到response对象的body区，通常用来返回JSON数据或者是XML数据，需要注意的呢，在使用此注解之后不会再走试图处理器，而是直接将数据写入到输入流中，他的效果等同于通过response对象输出指定格式的数据;

### springboot 配置+注解

	属性配置,自定义属性配置(在application.properties),其中，属性配置包括tomcaat配置、mysql数据源配置；  自定义属性配置包括单个属性获取、多个属性获取、多环境配置;
  
  	springboot注解;

### 数据库操作，事务管理 

	springboot数据库操作,模块包必须建立在启动类的包是平级或子级,否则无法自动建表;
	
	springbootJPA数据库操作;
	
	springboot事务管理;@EnableTransactionManagement、@Transactional;
