# tomcat7
tomcat7


#搭建手册
https://blog.51cto.com/spring1984/1773750

main class org.apache.catalina.startup.Bootstrap

vm
-Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager
-Djava.util.logging.config.file=D:\work\read_src\tomcat8\catalina_home\conf\logging.properties
-Dcatalina.home=D:\work\read_src\tomcat8\catalina_home
-Dcatalina.base=D:\work\read_src\tomcat8\catalina_home
-Djava.endorsed.dirs=D:\work_read\src\tomcat8\catalina_home\endorsed
-Djava.io.tmpdir=D:\work\read_src\tomcat8\catalina_home\temp