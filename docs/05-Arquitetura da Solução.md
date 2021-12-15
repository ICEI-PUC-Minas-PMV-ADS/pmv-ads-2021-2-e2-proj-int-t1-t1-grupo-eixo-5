# Arquitetura da Solução

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>

Definição de como o software é estruturado em termos dos componentes que fazem parte da solução e do ambiente de hospedagem da aplicação.

## Diagrama de Classes

A solução implementada conta com os seguintes módulos:
* IDE - Interface básica do sistema 
* Código do sistema - Conjunto de arquivos .csproj, .sln, .cs e frameworks e forms .NET 6.
* Banco de dados - Um banco de dados SQL Server integrado à aplicação.
* Compilador - Compilador da IDE (VS 2022).
* Executável - Possível executar pela IDE ou gerar um .exe do sistema.


## Modelo ER

O Modelo ER representa através de um diagrama como as entidades (coisas, objetos) se relacionam entre si na aplicação interativa.]

As referências abaixo irão auxiliá-lo na geração do artefato “Modelo ER”.

> - [Diagrama](img/diagrama.png)

## Tecnologias Utilizadas

Forms em .NET 6
SQL Server

## Deploy

Sistema pode ser executado pela IDE ou gerado um executável pela mesma.
