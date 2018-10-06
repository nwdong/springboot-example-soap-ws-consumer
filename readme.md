# it's based on https://github.com/spring-guides/gs-consuming-web-service/tree/master/complete

# how to build
firstly, start springboot-example-soap-ws-producer 
Or change POM to use wsdl file. WSDL file needs to be saved locally, as well as XSD files if refered by the WSDL file.

mvn clean install

# how to run
java -jar target/gs-consuming-web-service-0.1.0.jar

or run with parameter
java -jar target/gs-consuming-web-service-0.1.0.jar Poland

Then, in log, there is output as below
currency of Poland is PLN

# SoapActionCallback
It will be called after the request is marshalled, and before it is sent.
