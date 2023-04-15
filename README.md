####
### Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later


__Documentation__

https://www.jenkins.io/doc/



__Setup__

- To install plugins/Packages, go the the "manage Jenkins" section, go to Global Tool Configuration and select your required plugins from the list.

- To install Maven, we need to first install openJDK-8. jenkins runs on OpenJDK-11 but Maven runs on OpenJDK-8. This needs to be installed on the Jenkins host machine and we specify the home directory of OpenJDK-8 when configuring JDK installation. The home directory is "/usr/lib/jvm/java-1.8.0-openjdk-amd64".

Install OpenJDK-8
sudo apt update
sudo apt install openjdk-8-jdk -y



__Jenkins Environment Variables__

https://e.printstacktrace.blog/jenkins-pipeline-environment-variables-the-definitive-guide/






### Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
### Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql


