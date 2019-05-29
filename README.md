# Maven

1. Para executar o projeto:
```bash
mvn verify
# Para executar: Usar uma classe e executa a main dela. No nosso projeto não é necessário, porque está separado em 2 projetos diferentes
# Executa o servidor. 
mvn exec:java -Dexec.mainClass=io.grpc.examples.helloworld.HelloWorldServer
# Executa o cliente
mvn exec:java -Dexec.mainClass=io.grpc.examples.helloworld.HelloWorldClient
```