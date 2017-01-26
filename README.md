# Team3

To get running:
Install tomcat7, eclipse, maven
From inside the openmrs-core directory run
```
mvn clean install
```
Then move the logic-0.5.2.omod file to
```
home/.OpenMRS/modules/
```
You may need to create the modules directory

Once you have those steps, you may have to stop Tomcat which can be done with
```
sudo /etc/init.d/tomcat7 stop
```
Then cd to the webapp directory and run this command
```
mvn jetty:run
```
