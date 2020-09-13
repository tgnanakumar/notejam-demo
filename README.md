# Notejam Demo
Notejam application demo using AWS CloudFormation template which automatically provisions a single EC2 instance of type t3.micro in Stockholm (eu-north-1) region.  Installs all the required pre-requisites (Java, Git and Apache Maven) before starting the application.

## Pre-requisites
### Java
\# yum install -y java-1.8.0-openjdk

\# yum install -y java-1.8.0-openjdk-devel

### Git
\# yum install -y git

### Apache Maven
\# wget http://apache.mirrors.spacedump.net/maven/maven-3/3.6.3/binaries/apache-maven-3.6.3-bin.tar.gz

## Run Sprint Boot Application
\# mvn spring-boot:run
