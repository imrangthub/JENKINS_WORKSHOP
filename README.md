# Jenkins Workshop


=>C:\Program Files\Jenkins>java -jar jenkins.war

Add pluginh Git, GitHub, Deploy to container Plugin, Build Pipeline Plugin and more.


Simple project with Batch command:
-----------------------------------------------

In Build section select Execute Windows batch command:
   
      javac SimpleJavaApplication.java  
      java SimpleJavaApplication
 
 
 
Deploy to Tomcat
-----------------------------------------------

TomcatConfig:

			In server.xml set server port
			<Connector port="8585" protocol="HTTP/1.1" connectionTimeout="20000" redirectPort="8443" />

			In tomcat-users.xml set user
			<role rolename="manager"/>
			<role rolename="manager-gui"/>        
			<role rolename="admin"/>
			<role rolename="manager-script"/>
			<user username="admin" password="admin" roles="admin,manager,manager-gui,manager-script" /> 
			

Then Build a Jenkins **New Item**:



 ![FireShot Capture 014 - SpringBootSimpleWebDeploy Config  Jenkins  - localhost](https://user-images.githubusercontent.com/32607915/152630045-34a685a1-bdfa-466f-a989-876df9af5c52.png)

 

