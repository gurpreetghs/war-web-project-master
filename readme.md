# About this project

This project is a simple demo web application using Java annotations. It
runs on Java 7 and requires an application server.
# How do I build this project?

    mvn package

in your terminal. Your generated WAR file can be found as
*./target/wwp-1.0.0.war*.

# How do I run this project?

Navigate to Glassfish's directory. Start Glassfish by executing the following
command from the command line:

    glassfish4/bin/asadmin start-domain
 *http://localhost:8080/wwp-1.0.0*.
