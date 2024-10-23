# Template API REST

Template de API em .NET 8 com conexão ao banco de dados SQL Server, aplicando TDD (Test-Driven Development).

## Descrição

Este repositório contém um **template de API REST** desenvolvido em .NET 8, configurado com uma conexão ao banco de dados SQL Server. O projeto foi estruturado seguindo boas práticas de desenvolvimento, com foco na aplicação de **TDD (Test-Driven Development)** para facilitar a criação de testes automatizados desde o início do desenvolvimento.

A proposta deste template é **servir como base** para novos projetos de APIs, otimizando o processo de desenvolvimento ao fornecer uma estrutura inicial que inclui:
- Configuração de banco de dados SQL Server.
- Estrutura básica de TDD.
- Exemplo de controller, service, repository e testes unitários.
  
## Finalidade

O objetivo deste projeto é **fornecer um modelo** que pode ser utilizado para iniciar rapidamente o desenvolvimento de novas APIs em .NET 8. Ele economiza tempo ao fornecer uma estrutura já pronta e configurada, permitindo que o desenvolvedor foque na lógica de negócio da API sem precisar configurar tudo do zero.

**Nota**: Este template é apenas um ponto de partida. Recomenda-se que você o adapte conforme as necessidades específicas do seu projeto.

## Tecnologias Utilizadas

- **.NET 8**
- **SQL Server**
- **Entity Framework Core**
- **XUnit** para testes
- **Moq** para simulações (mocks) em testes

## Estrutura do Projeto

- **Controllers**: Responsáveis por receber as requisições HTTP e delegar as ações para os serviços.
- **Services**: Contêm a lógica de negócios da aplicação.
- **Repositories**: Camada de abstração para comunicação com o banco de dados.
- **Tests**: Conjunto de testes unitários seguindo o padrão TDD.

## Instalação e Configuração

### Requisitos

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [SQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads)

### Passos

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/template-api-rest.git
