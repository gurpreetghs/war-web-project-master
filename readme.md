It runs on Java 7 and requires an application server.
# BUILD

    mvn package

in your terminal. Your generated WAR file can be found as
*./target/wwp-1.0.0.war*.

# run
command from the command line:

    glassfish4/bin/asadmin start-domain
 *http://localhost:8080/wwp-1.0.0*.
