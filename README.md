# Minha API em Go com Docker Compose

Este repositório contém uma API simples desenvolvida em Go, juntamente com um ambiente Docker Compose para facilitar a execução da aplicação.

## Pré-requisitos

Certifique-se de ter o seguinte software instalado em sua máquina:

- Docker: [Instruções de Instalação do Docker](https://docs.docker.com/get-docker/)
- Docker Compose: [Instruções de Instalação do Docker Compose](https://docs.docker.com/compose/install/)

## Executando a API

Siga os passos abaixo para executar a API em um ambiente Dockerizado:

1. Clone este repositório para sua máquina local:

   ```bash
   git clone https://github.com/seu-usuario/minha-api-golang.git
Navegue até o diretório do projeto:

bash
Copy code
cd minha-api-golang
Crie e inicie os contêineres Docker usando o Docker Compose:

bash
Copy code
docker-compose up -d
A API estará acessível em: http://localhost:8080. Você pode acessar este endpoint para testar a API.

Desenvolvimento
Caso queira fazer modificações na API e testar localmente, siga as etapas abaixo:

Certifique-se de ter o Go instalado: Instruções de Instalação do Go

Navegue até o diretório do projeto:

bash
Copy code
cd minha-api-golang
Faça as modificações desejadas no código.

Compile e execute a aplicação:

bash
Copy code
go run main.go
Encerrando o Ambiente
Para parar e remover os contêineres Docker criados pelo Compose, execute:

bash
Copy code
docker-compose down
Isso encerrará a execução da API e removerá os contêineres.

Contribuição
Se você quiser contribuir para este projeto, fique à vontade para abrir um Pull Request. Será um prazer colaborar!

Licença
Este projeto está licenciado sob a Licença XYZ. Consulte o arquivo LICENSE para obter mais detalhes.
