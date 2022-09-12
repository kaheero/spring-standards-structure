# Arquitetura de um Projeto Spring Boot Baseado em Negócio

Este projeto representa uma base para o desenvolvimento de microsserviços com o Spring Boot.
Um modelo de projeto inicial adotado e modelado em cima do conceito de negócio do próprio projeto.

Muitas informações do que os pacotes e diretórios representam são auto descritivos, de fácil leitura
e facilmente adaptados.

Você consegue ter uma fácil identidade do que é seu projeto e com a separação dos pacotes de 
entidade do projeto, como por exemplo, **customer**, **order**, e afins, uma excelente forma de
representar seu serviço.

Quando você começa a obter um número relevante de pacotes de entidades, é preciso se perguntar se 
há uma boa separação de responsabilidades em seu projeto e o mesmo deveria ser **quebrado** em 
partes menores, aplicando o conceito de serviços com responsabilidades unicas (microsserviços).

Microsserviços são serviços que podem ser lançados de forma independente e são modelados com base
em um dominío de negócios. - Sam Newman

## O projeto

Entendendo as partes das nossa arquitetura.

### src

Contém o código fonte da aplicação com os testes unitários, arquivos de configuração e recursos.

### scripts

Adota os scripts.

### docs

Contém toda a documentação do nosso projeto.

### ci

Arquivos que são configurados para CI/CD do projeto.

### design

Utilizado principalmente para o ADR (Registros de Projeto Arquitetônico). Quando sua equipe quer
resolver um problema, e em seguida, apresentar uma solução, é aqui que se descreve como chegaram à
arquitetura e suas vantagens e desvantagens.

Dentro desse diretório eu tenho um Google ADR - muito utilizado atualmente pelos desenvolvedores.

### .github

Específico para o github reconhecer arquivos de configuração.
