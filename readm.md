# it's based on https://github.com/spring-guides/gs-consuming-web-service/tree/master/complete

# how to build
firstly, start springboot-example-soap-ws-producer (or change POM to use wsdl file)

mvn clean install

# how to run
java -jar target/gs-consuming-web-service-0.1.0.jar

or run with parameter
java -jar target/gs-consuming-web-service-0.1.0.jar Poland

# SoapActionCallback
It will be called after the request is marshalled, and before it is sent.
