# UniTime_Integration_HUF
For HUF University


1- Create a Dynamic Web Project in new workspace
2- Right Click on Project => Configure => Convert to Maven Project
3- Change pom.xml with backup project
4- Copy all folders from backup project to newly created project
5- Edit .classpath file according to backup project file. 
6- Update maven project
7- Run => mvn clean install
8- Project => Clean & Build Project
9- Add Tomcat server 8
10- Add mysql_connector to tomcat lib folders
11- Add "projectname.properties" file to tomcat/conf folder
12- In your $CATALINA_BASE/conf/context.xml add block below before </Context>
	<Resources cachingAllowed="true" cacheMaxSize="100000" />
13- Run on server
