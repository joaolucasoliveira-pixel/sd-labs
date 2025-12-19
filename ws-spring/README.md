# Calculadora Web - Spring Boot

Aplicação web simples de calculadora usando Spring Boot e interface HTML.

## Pré-requisitos

- Java 8 ou superior
- Maven

## Como executar

1. Clone ou baixe o projeto

2. No terminal, navegue até a pasta do projeto e execute:

```bash
mvn clean install
mvn spring-boot:run
```

3. Acesse no navegador:
   - Interface: http://localhost:8080/index.html

## Endpoints da API

- Somar: `http://localhost:8080/somar/5/3`
- Subtrair: `http://localhost:8080/subtrair/5/3`
- Multiplicar: `http://localhost:8080/multiplicar/5/3`
- Dividir: `http://localhost:8080/dividir/10/2`
