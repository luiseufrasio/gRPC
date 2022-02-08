# Payara gRPC implementation

This is the repo for the Payara gRPC implementation. To use gRPC follow the next steps:

To use the gRPC implementation you must build the current project:

```
mvn clean install
```

The resulted jar with name grpc-support-[version number].jar, must be included into the payara modules folder.

> Recomendation: First build payara server and then add the jar on the modules folder


If you want to see more details about to create a war application to enable gRPC, please see the following example [Payara-Examples gRPC](https://github.com/payara/Payara-Examples/tree/master/grpc).