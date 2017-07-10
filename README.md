# AWS-RDS-BeanStalk-S3-EC2-WordpressApplication
Wordpress Application (compatible on JEE Server Tomcat) on Amazon Web Services (MySQL RDS, Tomcat Elastic Beanstalk, S3 Storage).

Read the "wp-config.php" file for configuration details.

This app is functional on URL "http://default-environment.nyfmcgwv95.us-west-2.elasticbeanstalk.com/".



Using JAVA'S JAR command/utility, package this entire code and build a WAR file for deployment onto the remote AWS Elastic Beanstalk Server (Tomcat 8 running on Java 8)

Command:

            JAR CVF BlogApplication.WAR
            
            
Once the WAR file is generated, publish or deploy on your AWS node.
