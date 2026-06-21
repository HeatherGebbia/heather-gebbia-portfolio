# Customer Agreement Web Application

A full-stack customer agreement management system demonstrating a complete modernization journey from **VB.NET Web Forms** to **C# Web Forms** and finally to **ASP.NET Core Razor Pages with a REST API architecture**.

The application allows administrators to create and manage customizable questionnaires while customers can create, save, submit, and review agreements. The solution is deployed to **Microsoft Azure** using **Azure App Services** and **Azure SQL Database**.

This project serves as a portfolio piece showcasing modern .NET development, application modernization, API design, cloud deployment, and database-driven web applications.

---

## 🚀 Live Demo

### Portfolio Landing Page

🔗 https://customeragreement-portfolio-fxhnd4d0b4avajcy.eastus2-01.azurewebsites.net/

> **Note:** The Azure SQL Database uses serverless auto-pause to reduce hosting costs. If the database is asleep, click **Wake Up Database** and wait approximately 15–30 seconds before launching the demos.

### Available Demonstrations

* Original C# Web Forms Version
* Modernized ASP.NET Core Razor Pages + REST API Version

*(No authentication required — demo/test data only.)*

---

## 📂 Repository

This repository contains the source code for the modernized **ASP.NET Core Razor Pages** version of the Customer Agreement application.

### Modernization Timeline

1. Original Application – VB.NET Web Forms
2. Phase 1 – Migration to C# Web Forms
3. Phase 2 – Migration to ASP.NET Core Razor Pages
4. Phase 3 – Introduction of REST API Architecture
5. Azure Deployment using App Services and Azure SQL Database

---

## ✨ Features

### Customer Features

* Create customer agreements
* Save agreements as drafts
* Submit completed agreements
* View submitted agreements
* Dynamic questionnaire rendering
* Conditional and dependent questions

### Administrative Features

* Manage questionnaires
* Manage sections
* Manage questions
* Manage list values
* Manage dependent questions
* Manage notification templates
* Preview questionnaires before publishing
* Search, filter, and sort completed agreements

### Technical Features

* REST API architecture
* DTO-based API communication
* Entity Framework Core data access
* Feature flags with API/database fallback support
* Azure SQL Database integration
* Azure App Service deployment

---

## 🏗️ Architecture

### Front End

* ASP.NET Core Razor Pages
* HTML
* CSS
* JavaScript
* jQuery

### API Layer

* ASP.NET Core Web API
* RESTful endpoints
* DTO-based communication

### Data Layer

* Entity Framework Core
* SQL Server
* Azure SQL Database

### Cloud Hosting

* Azure App Services
* Azure SQL Database
* Azure App Settings
* Azure Connection Strings

---

## 🛠️ Technologies Used

* C#
* ASP.NET Core Razor Pages
* ASP.NET Core Web API
* Entity Framework Core
* SQL Server
* Azure SQL Database
* Azure App Services
* HTML
* CSS
* JavaScript
* jQuery
* Git
* GitHub

---

## 🎯 Technical Highlights

* Executed a complete modernization project from VB.NET Web Forms → C# Web Forms → ASP.NET Core Razor Pages
* Designed and implemented a REST API layer to support application functionality
* Migrated administrative pages from direct database access to API-driven architecture
* Implemented Entity Framework Core with DTO-based API communication
* Added feature flags supporting API rollout with database fallback
* Designed reusable DTOs and controller endpoints for questionnaires, sections, questions, lists, notifications, and agreements
* Deployed multiple Azure App Services and Azure SQL Database environments
* Used Git and GitHub for source control and deployment workflows

---

## 🔐 Security Note

This repository does **not** contain any sensitive information.

* Connection strings are stored in Azure App Service Configuration
* Development secrets are stored using User Secrets
* API configuration values are stored outside source control
* No credentials, API keys, or production secrets are committed to GitHub

---

## 📈 Future Enhancements

* Microsoft Graph integration for automated email notifications
* Rich text/HTML editor for questionnaire formatting
* Export completed agreements to Excel
* Role-based authorization
* Audit history and change tracking
* CI/CD deployment pipeline using Azure DevOps or GitHub Actions

---

## 👩‍💻 About Me

This project is part of my software development portfolio and demonstrates experience with:

* Application modernization
* ASP.NET Core development
* REST API design
* Entity Framework Core
* Azure cloud deployment
* SQL Server development

### Portfolio

🔗 https://heathergebbia.github.io/heather-gebbia-portfolio/

### LinkedIn

💼 https://www.linkedin.com/in/heather-gebbia7

