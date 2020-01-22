# FornecedorMS
Projeto Fornecedor do curso Microservices com Spring Cloud: Registry, Config Server e Distributed Tracing da Alura

# fornecedor.yml: arquivo de configuração q fica no flie-system do ambiente, lido pelo config-server antes de subir
spring:
  datasource:
      password:
      username: root
      url: jdbc:mysql://localhost:3306/fornecedor?useTimezone=true&serverTimezone=UTC

  
  jpa:
    hibernate:
      ddl-auto: update