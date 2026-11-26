# POO-Lab — Banco digital

Laboratório de Programação Orientada a Objetos em Java. O projeto demonstra contas corrente e poupança, depósitos, saques, transferências com tarifa, extratos e tratamento de exceções. As contas ficam em memória durante a execução.

## Compilar, testar e executar

Requer Java 21 e Maven.

```sh
mvn clean verify
java -jar target/banco-digital-1.0-SNAPSHOT.jar
```

O Maven executa a suíte JUnit 5 antes de empacotar o JAR. A demonstração imprime os saldos após uma transferência e mostra o tratamento de uma conta inexistente.
