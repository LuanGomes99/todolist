# Lista de Tarefas - Backend

Este é um projeto de back-end em Java usando o Spring Boot, realizado no **Curso de Java da Rocketseat** para criar uma aplicação de lista de tarefas. A aplicação permite que os usuários criem, atualizem,
e visualizem suas tarefas. Além disso, há autenticação de usuário para garantir que apenas usuários autenticados possam acessar suas tarefas.

<br>

## Recursos
* Autenticação de usuário (Login e Registro)
* CRUD de tarefas (Criar, Ler, Atualizar e Deletar)
* Campos de tarefa incluem: título, descrição, data de vencimento, prioridade, etc.
* Validações de entrada para garantir que os dados sejam corretos
* Banco de dados para armazenar informações de tarefas

## Tecnologias Utilizadas
* Java
* Spring Boot
* Spring Data JPA
* H2 Database (para fins de demonstração, você pode usar um banco de dados diferente em produção)
* Maven para gerenciamento de dependências

## HTTP Request
As requisições HTTP para este projeto foram testadas no APIdog. Você pode encontrar detalhes sobre como usar o APIdog neste <a href="https://apidog.com/help/category/api-documentation" target="_blank">link da documentação</a>. Lá você encontrará informações sobre os endpoints, autenticação e exemplos de solicitações e respostas.
Certifique-se de verificar a documentação da API para entender como interagir com este projeto de lista de tarefas de forma eficaz.

<br>

# Deploy
Este projeto foi implantado com sucesso no **Render.com**. O Render oferece uma plataforma de hospedagem simples e eficaz que permite implantar aplicativos com facilidade. <br>
Este projeto foi implementado usando um contêiner **Docker** para facilitar a configuração e a execução da aplicação. O arquivo Docker utilizado está incluído neste repositório para referência.

## Arquivo Docker
Você pode encontrar o arquivo Docker na raiz deste repositório com o nome Dockerfile. Este arquivo contém as instruções para criar uma imagem Docker personalizada que inclui todas as dependências necessárias para executar a aplicação. O Render.com é compatível com contêineres Docker, o que torna a implantação e a escalabilidade da aplicação muito mais simples.
