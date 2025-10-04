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

Database: PostgreSQL (or specify your choice, e.g., SQL Server) via Entity Framework Core

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
You can run the application directly from your IDE (Visual Studio/Rider) by setting the CRM-Blazor-Aspire.AppHost project as the startup project and pressing 'Run'.

Alternatively, you can use the command line:

dotnet run --project ./CRM-Blazor-Aspire.AppHost/CRM-Blazor-Aspire.AppHost.csproj

Access the application:
Once the application starts, the .NET Aspire dashboard will launch. You can find the URLs for the Blazor frontend and any backend APIs in the dashboard's resource list.

🏛️ Architectural Overview
The solution is structured to be scalable and maintainable, with .NET Aspire orchestrating the different parts of the application.

CRM-Blazor-Aspire.AppHost: The .NET Aspire host project. It defines which projects and resources (like databases) are part of the application and how they connect.

CRM-Blazor-Aspire.ServiceDefaults: A shared project containing default configurations for resilience, service discovery, and telemetry.

CRM-Blazor-Aspire.WebApp: The Blazor Web App project, which contains all the UI components and client-side logic.

CRM-Blazor-Aspire.Api: An ASP.NET Core API project that handles business logic and data access, serving data to the Blazor front end.

This separation allows for better organization and the potential to scale different parts of the application independently.

🤝 Contributing
This is a personal learning project to showcase and develop my skills. Therefore, I am not accepting contributions at this time. However, feel free to fork the repository for your own educational purposes.

📄 License
Copyright © 2024 Gabriel [GabiestDev]. All Rights Reserved.
