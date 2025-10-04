🇬🇧 English
Blazor Aspire CRM
A modern Customer Relationship Management (CRM) web application built with Blazor Web App and orchestrated by .NET Aspire. This project serves as a practical exploration to deepen my expertise in C#, the .NET ecosystem, and modern cloud-native development practices.

🚀 Project Goals
The primary goal of this repository is to serve as a hands-on learning project. It's a journey to master and apply advanced concepts in the .NET stack, focusing on:

Blazor: Building interactive, component-based user interfaces with C#.

.NET Aspire: Simplifying the development and deployment of cloud-native, distributed applications.

Clean Architecture: Implementing a robust, scalable, and maintainable application structure.

C# and .NET: Leveraging the latest features of the language and framework to build a real-world application.

Entity Framework Core: Managing data persistence and complex database operations.

✨ Features
The CRM aims to provide essential features for managing customer relationships:

Dashboard: An overview of key metrics and activities.

Contact Management: Create, view, edit, and delete customer contacts.

Company Management: Track companies and link them to contacts.

Sales Pipeline: Visualize and manage sales opportunities through different stages.

User Authentication: Secure access to the application.

(Planned) Reporting: Generate reports on sales activities and customer data.

(Planned) Interaction Logging: Log calls, emails, and meetings with contacts.

🛠️ Technologies Used
This project is built using a modern .NET technology stack:

Backend & Frontend: .NET 8, C# 12

UI Framework: Blazor Web App (Server-side rendering and Interactive components)

Orchestration: .NET Aspire

Database: PostgreSQL via Entity Framework Core

API: RESTful APIs built with ASP.NET Core

Authentication: ASP.NET Core Identity

⚙️ Getting Started
Follow these instructions to get the project up and running on your local machine.

Prerequisites
.NET 8 SDK

.NET Aspire Workload

A container runtime like Docker Desktop

An IDE like Visual Studio 2022 or JetBrains Rider.

Installation & Running
Clone the repository:

git clone [https://github.com/GabiestDev/CRM-Blazor-Aspire.git](https://github.com/GabiestDev/CRM-Blazor-Aspire.git)
cd CRM-Blazor-Aspire

Navigate to the .AppHost project:
The CRM-Blazor-Aspire.AppHost project is the entry point for running the application with .NET Aspire.

Run the application:
Run from your IDE by setting the CRM-Blazor-Aspire.AppHost project as the startup project and pressing 'Run'.

Or via the command line:

dotnet run --project ./CRM-Blazor-Aspire.AppHost/CRM-Blazor-Aspire.AppHost.csproj

Access the application:
Once started, the .NET Aspire dashboard will launch. You can find the URLs for the Blazor frontend and any backend APIs in the dashboard.

🏛️ Architectural Overview
The solution is structured to be scalable and maintainable:

CRM-Blazor-Aspire.AppHost: The .NET Aspire host project.

CRM-Blazor-Aspire.ServiceDefaults: A shared project for default configurations (resilience, service discovery).

CRM-Blazor-Aspire.WebApp: The Blazor Web App project (UI components, client-side logic).

CRM-Blazor-Aspire.Api: An ASP.NET Core API project (business logic, data access).

🤝 Contributing
This is a personal learning project. Therefore, contributions are not being accepted at this time.


🇧🇷 Português (Brasil)
Blazor Aspire CRM
Uma moderna aplicação web de Gerenciamento de Relacionamento com o Cliente (CRM) construída com Blazor Web App e orquestrada pelo .NET Aspire. Este projeto serve como uma exploração prática para aprofundar meu conhecimento em C#, no ecossistema .NET e em práticas modernas de desenvolvimento nativo para a nuvem.

🚀 Objetivos do Projeto
O objetivo principal deste repositório é servir como um projeto de aprendizado prático. É uma jornada para dominar e aplicar conceitos avançados na stack .NET, com foco em:

Blazor: Construindo interfaces de usuário interativas e baseadas em componentes com C#.

.NET Aspire: Simplificando o desenvolvimento e a implantação de aplicações distribuídas e nativas para a nuvem.

Arquitetura Limpa: Implementando uma estrutura de aplicação robusta, escalável e de fácil manutenção.

C# e .NET: Utilizando os recursos mais recentes da linguagem e do framework para construir uma aplicação do mundo real.

Entity Framework Core: Gerenciando a persistência de dados e operações complexas de banco de dados.

✨ Funcionalidades
O CRM visa fornecer funcionalidades essenciais para gerenciar o relacionamento com clientes:

Dashboard: Uma visão geral das principais métricas e atividades.

Gerenciamento de Contatos: Crie, visualize, edite e exclua contatos de clientes.

Gerenciamento de Empresas: Acompanhe empresas e vincule-as a contatos.

Funil de Vendas: Visualize e gerencie oportunidades de vendas em diferentes estágios.

Autenticação de Usuários: Acesso seguro à aplicação.

(Planejado) Relatórios: Gere relatórios sobre atividades de vendas e dados de clientes.

(Planejado) Registro de Interações: Registre chamadas, e-mails e reuniões com contatos.

🛠️ Tecnologias Utilizadas
Este projeto foi construído usando uma stack de tecnologia .NET moderna:

Backend & Frontend: .NET 8, C# 12

UI Framework: Blazor Web App

Orquestração: .NET Aspire

Banco de Dados: PostgreSQL via Entity Framework Core

API: APIs RESTful construídas com ASP.NET Core

Autenticação: ASP.NET Core Identity

⚙️ Como Começar
Siga estas instruções para obter o projeto e executá-lo em sua máquina local.

Pré-requisitos
.NET 8 SDK

Workload do .NET Aspire

Um ambiente de execução de contêineres como o Docker Desktop

Uma IDE como o Visual Studio 2022 ou JetBrains Rider.

Instalação e Execução
Clone o repositório:

git clone [https://github.com/GabiestDev/CRM-Blazor-Aspire.git](https://github.com/GabiestDev/CRM-Blazor-Aspire.git)
cd CRM-Blazor-Aspire

Navegue até o projeto .AppHost:
O projeto CRM-Blazor-Aspire.AppHost é o ponto de entrada para executar a aplicação com o .NET Aspire.

Execute a aplicação:
Execute a partir da sua IDE definindo o projeto CRM-Blazor-Aspire.AppHost como o projeto de inicialização e pressionando 'Executar'.

Ou através da linha de comando:

dotnet run --project ./CRM-Blazor-Aspire.AppHost/CRM-Blazor-Aspire.AppHost.csproj

Acesse a aplicação:
Assim que a aplicação iniciar, o painel do .NET Aspire será aberto. Você pode encontrar as URLs para o frontend Blazor e quaisquer APIs de backend na lista de recursos do painel.

🏛️ Visão Geral da Arquitetura
A solução é estruturada para ser escalável e de fácil manutenção:

CRM-Blazor-Aspire.AppHost: O projeto host do .NET Aspire.

CRM-Blazor-Aspire.ServiceDefaults: Um projeto compartilhado para configurações padrão (resiliência, descoberta de serviço).

CRM-Blazor-Aspire.WebApp: O projeto Blazor Web App (componentes de UI, lógica do cliente).

CRM-Blazor-Aspire.Api: Um projeto de API ASP.NET Core (lógica de negócios, acesso a dados).

🤝 Contribuições
Este é um projeto de aprendizado pessoal. Portanto, não estou aceitando contribuições no momento.

