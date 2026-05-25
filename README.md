🚀 Projeto E-commerce com Microsserviços

Bem-vindo ao meu projeto de estudos em arquitetura de microsserviços!
Este repositório faz parte do curso que estou realizando para aprofundar meus conhecimentos em desenvolvimento backend, containers, bancos de dados, mensageria e comunicação entre serviços.

O objetivo é construir uma aplicação de E-commerce distribuída, utilizando diferentes tecnologias modernas do mercado.

📚 Tecnologias e Conceitos Estudados

Durante o desenvolvimento deste projeto estou aprendendo e praticando:

🐳 Docker
🐘 PostgreSQL
🍃 MongoDB
🐇 RabbitMQ
🧠 Microsserviços
🔐 Autenticação e autorização
📦 Mensageria entre serviços
⚡ APIs REST
☕ Java
🟩 Node.js + Express
🗄️ DBeaver
🔄 Comunicação assíncrona
📡 Integração entre bancos SQL e NoSQL
🏗️ Arquitetura do Projeto

O sistema será dividido em múltiplos microsserviços independentes.

🔐 Auth Service

Responsável por:

Cadastro de usuários
Login
Autenticação
Geração de tokens
Tecnologias:
Node.js
Express
PostgreSQL
📦 Product Service

Responsável por:

Cadastro de produtos
Estoque
Consulta de produtos
Tecnologias:
Java
PostgreSQL
💰 Sales Service

Responsável por:

Registro de vendas
Histórico de pedidos
Processamento de compras
Tecnologias:
Java
MongoDB
🐇 Comunicação entre Microsserviços

A comunicação assíncrona será feita utilizando o RabbitMQ.

Exemplo de fluxo:

Uma venda é criada no Sales Service
O serviço publica uma mensagem no RabbitMQ
O Product Service consome essa mensagem
O estoque do produto é atualizado automaticamente
🗃️ Bancos de Dados
Serviço	Banco
Auth Service	PostgreSQL
Product Service	PostgreSQL
Sales Service	MongoDB
🐳 Docker

Todos os serviços e bancos serão executados em containers Docker.

O projeto utilizará:

Docker
Docker Compose

Containers previstos:

PostgreSQL
MongoDB
RabbitMQ
Microsserviços
🎯 Objetivo do Projeto

Este projeto foi criado com foco em aprendizado prático de:

Arquitetura de microsserviços
Separação de responsabilidades
Escalabilidade
Comunicação entre serviços
Containers
Persistência de dados
Backend moderno
📈 Futuras Implementações
API Gateway
Service Discovery
JWT Authentication
Refresh Tokens
Observabilidade
Logs centralizados
Deploy em nuvem
Kubernetes
CI/CD
Testes automatizados
🛠️ Status do Projeto

🚧 Em desenvolvimento
📖 Projeto utilizado para estudos e evolução técnica

👨‍💻 Autor

- Nicolas Fabretti
Desenvolvido durante meus estudos em backend e microsserviços.
