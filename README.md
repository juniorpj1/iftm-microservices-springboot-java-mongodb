# IFTM: projeto back-end com mongodb

## Projeto desenvolvido durante a graduação para exemplificar e praticar a arquitetura da Netflix que utiliza tecnologias modernas.

## Tecnologias utilizadas:

- Java 17
- SpringBoot
- EurekaServer
- API Gateway
- Load Balancing
- MongoDB
- Postman
- IntelliJ
- Git
- GitHub

## Como executar o projeto:

- Clonar o repositório
- Abrir o projeto no IntelliJ
- Executar o projeto na seguinte ordem: Eureka Server, API Gateway e a aplicação (habilite multi instâncias para testar o load balancing)
- Executar as requisições no Postman usando a URL do API Gateway
- Acessando o Eureka: http://localhost:8761/
- Acessando o Serviço de Employees http://localhost:8765/eureka-client-software-house/api/v1/employees