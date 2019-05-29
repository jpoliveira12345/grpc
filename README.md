# Maven

1. Run in this directory:
```bash
mvn verify
# Run the server
mvn exec:java -Dexec.mainClass=io.grpc.examples.helloworld.HelloWorldServer
# In another terminal run the client
mvn exec:java -Dexec.mainClass=io.grpc.examples.helloworld.HelloWorldClient
```