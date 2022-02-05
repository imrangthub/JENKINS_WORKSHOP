# Jenkins Workshop


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

 
 
 ![image](https://user-images.githubusercontent.com/32607915/152629944-aee2eaf4-6740-4043-8e82-61243c8efc56.png)

