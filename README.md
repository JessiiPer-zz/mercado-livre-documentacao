# Projeto mercado livre - Encurtador de URL

  Queremos prover a equipe de marketing ferramentas que possibilitem o envio de
comunicações por canais de mensageria, tais como SMS e Twitter. Nestes canais, é muito
importante que as comunicações sejam curtas, assim faz-se necessário o desenvolvimento de
um encurtador de URLs.

# Índice

* [Requisitos](#requisitos)
* [Tecnologias Utilizadas](#tecnologias-utilizadas)
* [Diagrama de arquitetura](#diagrama-de-arquitetura)

## Requisitos

* Dada uma URL longa, ele devolva uma URL curta.
* Dada a URL curta, ele devolva a URL original.
* Seja possível obter-se estatísticas de uso do serviço.
* Deve ser possível escalar o serviço para atender grandes volumes de requisições.
* 90% das requisições devem responder em menos de 10 ms.
* Deve ser permitir apagar as URLs curtas.
* E, obviamente que o usuário acesse a URL original quando entrar com a URL curta
no navegador

## Tecnologias Utilizadas

* Linguagem Java (versão 8)
* Spring Boot 2.1
* Maven
* Redis
* Spring Cloud Netflix
* Spring Cloud Config Server
* Spring Security
* Spring Sleuth + Papertrail
* Spring Data
* Junit 4 + Coverage (81,5% de cobertura)
* Docker

## Diagrama de arquitetura
![Diagrama de arquitetura](https://github.com/JessiiPer/mercado-livre-documentacao/blob/master/arquitetura.png)

## Melhorias Futuras

* Utilizar o Zipkin para monitoramento de logs.
* Deixar o Redis como cache e utilizar um outro banco de dados.
* Utilizar containers


## Autoria
* Jessica Pereira Rocha

