# Olá, sou Marcos Vítor! 

## Engenheiro de Software Full Stack | .NET & Azure | AI Solutions | TS | Node

### MAIN STACK & CORE SKILLS

* [cite_start]**Backend:** .NET 8/10, C#, ASP.NET Web API, .NET Core, .NET Framework (4.7/4.8), Node.js (NestJS)[cite: 4, 8].
* [cite_start]**Cloud & DevOps:** Azure (App Services, Functions, Service Bus, Blob Storage, Key Vault), Docker, CI/CD Pipelines (Azure DevOps)[cite: 5, 9, 23].
* [cite_start]**Frontend:** Angular 12+ (Signals/RxJS), React (Hooks/Context), TypeScript, SignalR (Real-time)[cite: 8, 15, 30].
* [cite_start]**Data & Messaging:** SQL Server (Query Optimization), PostgreSQL, MongoDB, Redis, RabbitMQ, Azure Service Bus[cite: 9, 10, 22].
* [cite_start]**Architecture & Security:** Clean Architecture, DDD, SOLID, Microservices, CQRS, OAuth2, JWT[cite: 5, 10, 21].

---

### Destaques de Engenharia & Projetos Recentes

Aqui estão alguns desafios técnicos que solucionei recentemente utilizando o padrão **XYZ do Google**:

- [cite_start]**Arquitetura de Upload Cloud-Native:** Desenvolvi um módulo desacoplado usando **.NET** e **SignalR** para uploads simultâneos massivos no **Azure Blob Storage**, eliminando gargalos de UI e aumentando a produtividade médica[cite: 15].
- [cite_start]**Automação com IA:** Projetei Background Services integrados a **Agentes de IA (OCR/LLM)** para extração automática de dados sensíveis de laudos médicos, eliminando erros de input manual através do cruzamento de dados com Firebird[cite: 16].
- [cite_start]**Modernização de Legado:** Liderei a migração de sistemas de **.NET Framework 4.8 para .NET 8** e endpoints SOAP para **REST APIs** centralizadas, implementando camadas de auditoria e segurança[cite: 17].
- [cite_start]**Performance de Dados:** Reduzi o tempo de resposta em filtros de grandes volumes de dados governamentais em **3-5 segundos** ao refatorar queries complexas no SQL Server via **Dapper**[cite: 22].

---

### Metodologias & Conceitos

![Scrum](https://img.shields.io/badge/Agile-SCRUM-blue?style=for-the-badge&logo=scrum&logoColor=white)
![Clean Arch](https://img.shields.io/badge/Architecture-Clean_Architecture-success?style=for-the-badge&logo=codeproject&logoColor=white)
![DDD](https://img.shields.io/badge/Design-DDD-orange?style=for-the-badge&logo=domaindrivenndesign&logoColor=white)
![Microservices](https://img.shields.io/badge/Architecture-Microservices-red?style=for-the-badge&logo=serverless&logoColor=white)
![CI/CD](https://img.shields.io/badge/DevOps-CI%2FCD-blueviolet?style=for-the-badge&logo=github-actions&logoColor=white)

---

### Tech Stack Detalhada

**Backend & Mensageria**
![.NET](https://img.shields.io/badge/.NET_8/10-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Azure Service Bus](https://img.shields.io/badge/Service_Bus-0078D7?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Cloud & DevOps**
![Azure](https://img.shields.io/badge/Azure-007FFF?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Key Vault](https://img.shields.io/badge/Key_Vault-0078D7?style=for-the-badge&logo=microsoft-azure&logoColor=white)

**Frontend & Mobile**
![Angular](https://img.shields.io/badge/Angular_12+-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![SignalR](https://img.shields.io/badge/SignalR-181717?style=for-the-badge&logo=dotnet&logoColor=white)

---

### DNA Técnico
```csharp
public class MarcosVitor : PlenoSoftwareEngineer
{
    public string[] CoreSkills => new[] 
    { 
        "Clean Architecture", 
        "DDD & SOLID", 
        "Microservices (Event-Driven)",
        "Cloud Governance (Azure)"
    };
    
    public void SolveComplexProblem(Problem issue)
    {
        var solution = Analyze(issue);
        solution.ApplyPattern(DesignPatterns.CQRS | DesignPatterns.Strategy);
        solution.Optimize(Metric.LowLatency);
        
        Deploy(solution, Environment.AzureCloud);
    }
}
