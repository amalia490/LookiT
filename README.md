# Micro-Social Platform

[![ASP.NET Core](https://img.shields.io/badge/Framework-ASP.NET%20Core%20MVC-512bd4)](https://dotnet.microsoft.com/)
[![Entity Framework](https://img.shields.io/badge/ORM-EF%20Core-blueviolet)](https://learn.microsoft.com/en-us/ef/core/)

###  Project Overview
A modern web application built with **C#** and **ASP.NET Core MVC**, designed to simulate core functionalities of popular social networks like Instagram or Facebook. The project focuses on data security, role-based access control, and intelligent content moderation.

---

###  Key Features

| Category | Description |
| :--- | :--- |
| **User Roles** | Multi-level access: Unregistered Visitor, Registered User, and Administrator. |
| **Privacy & Profiles** | Public/Private profiles with a "Follow" request system (unidirectional). |
| **Content** | Multimedia posts (Text, Image, Video), comments, and Like reactions. |
| **Groups** | Community hubs moderated by creators, featuring member approval (Join) and messaging. |
| **Personalized Feed** | Custom timeline displaying posts from followed users in reverse chronological order. |

---

### AI Companion Integration
The platform features an **Automated Content Filtering** module powered by Artificial Intelligence.
- **Purpose:** Scans post and comment text in real-time before publication.
- **Action:** If hate speech or inappropriate language is detected, the system blocks the post and provides a friendly warning to the user.
- **Implementation:** Integration via API (e.g., OpenAI or ML.NET) for Natural Language Processing (NLP).

---

### Architecture & Stack
* **Pattern:** Model-View-Controller (MVC) with a clear separation of concerns.
* **Database:** SQL Server, utilizing the *Code First* approach via Entity Framework Core.
* **Security:** ASP.NET Identity for robust authentication and role management.
* **Validation:** Strict server-side (Data Annotations) and client-side data validation.

---

### Seed Data
The database is pre-populated with **realistic seed data** for immediate testing:
- **3 Users** with distinct roles (Admin, Registered Users).
- **3 Groups** with diverse descriptions.
- **5 Posts** containing multimedia content and sample reactions.

---

###  Administration
The Administrator maintains full control over the platform, with the ability to delete any content (messages, groups, or posts) that violates community guidelines, ensuring a safe user environment.
