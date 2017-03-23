# NIFI-OPCUA

Nifi service and processors for accessing data via OPC UA

This project depends on the OPC Foudation UA Java implementation found here https://github.com/OPCFoundation/UA-Java

Use the directions provided to build the opc-ua-stack.XX.jar or an already build version is available in lib folder of the project, install it using
mvn install:install-file -Dfile=./lib/opc-ua-stack-XX.jar -DgroupId=org.opcfoundation.ua -DartifactId=opc-ua-stack -Dversion=1.03.340.0-SNAPSHOT -Dpackaging=jar
    
Place the jar in Nifi's lib folder as well.


