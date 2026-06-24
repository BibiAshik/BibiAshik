<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,19,20,21,24&height=200&section=header&text=Bibi%20Ashik%20B%20A&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Java%20Backend%20Developer%20%7C%20Spring%20Boot%20%7C%20REST%20APIs&descAlignY=58&descAlign=50" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3500&pause=800&color=A78BFA&center=true&vCenter=true&multiline=false&width=700&lines=Building+Secure+Backend+Systems+with+Java;Spring+Boot+%7C+Spring+Security+%7C+JWT;Designing+REST+APIs+%26+Microservices;B.E.+ECE+%E2%86%92+Backend+Developer+%7C+Chennai)](https://git.io/typing-svg)

<br/>

![Degree](https://img.shields.io/badge/B.E.%20Electronics%20%26%20Communication-Sri%20Sairam%20Institute%20of%20Technology-7C3AED?style=flat-square&logo=graduation-cap&logoColor=white)
![Batch](https://img.shields.io/badge/Batch-2022--2026-5B21B6?style=flat-square)
![Location](https://img.shields.io/badge/Chennai%2C%20Tamil%20Nadu-India-4C1D95?style=flat-square&logo=googlemaps&logoColor=white)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-bibiashik05-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bibiashik05)
[![GitHub](https://img.shields.io/badge/GitHub-BibiAshik-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BibiAshik)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-D946EF?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bibiashik05@gmail.com)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=BibiAshik&color=7C3AED&style=flat-square&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/BibiAshik?color=5B21B6&style=flat-square&logo=github&label=Followers)
![Stars](https://img.shields.io/github/stars/BibiAshik?affiliations=OWNER&color=4C1D95&style=flat-square&logo=github&label=Stars)

</div>

---

## ◈ About Me

```yaml
name        : Bibi Ashik B A
role        : Java Backend Developer (Fresher)
education   : B.E. Electronics & Communication Engineering — 2026
institution : Sri Sairam Institute of Technology, Chennai
location    : Chennai, Tamil Nadu, India
```

I am a self-taught Java backend developer who transitioned from Electronics & Communication Engineering into software through a backend internship that sparked a genuine interest in server-side architecture. Since then I have built three production-grade projects independently — a multi-tenant SaaS platform, a canteen pre-order system, and a real-time payment verification engine — each one a deliberate step up in complexity, security design, and system thinking.

My focus is on writing clean, secure, and maintainable backend code using the Java and Spring ecosystem. I care about understanding *why* a design decision is made, not just *how* to implement it — which is why concepts like stateless JWT authentication, pessimistic locking for concurrency, and idempotency constraints show up naturally in my work rather than as afterthoughts.

**Open To:** Java Backend Developer roles · Full-Stack opportunities (Spring Boot + JS frontend) · Service companies (TCS, Infosys, Wipro) · Product startups in India

---

## ◈ Tech Stack

<div align="center">

**Languages & Core**

[![Java](https://skillicons.dev/icons?i=java)](https://java.com)&nbsp;
[![MySQL](https://skillicons.dev/icons?i=mysql)](https://mysql.com)&nbsp;
[![HTML](https://skillicons.dev/icons?i=html)](https://developer.mozilla.org/en-US/docs/Web/HTML)&nbsp;
[![CSS](https://skillicons.dev/icons?i=css)](https://developer.mozilla.org/en-US/docs/Web/CSS)&nbsp;
[![JavaScript](https://skillicons.dev/icons?i=js)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

**Backend & Frameworks**

[![Spring](https://skillicons.dev/icons?i=spring)](https://spring.io)&nbsp;
[![Maven](https://skillicons.dev/icons?i=maven)](https://maven.apache.org)&nbsp;
[![Hibernate](https://skillicons.dev/icons?i=hibernate)](https://hibernate.org)

**DevOps & Tooling**

[![Git](https://skillicons.dev/icons?i=git)](https://git-scm.com)&nbsp;
[![GitHub](https://skillicons.dev/icons?i=github)](https://github.com)&nbsp;
[![Docker](https://skillicons.dev/icons?i=docker)](https://docker.com)&nbsp;
[![Postman](https://skillicons.dev/icons?i=postman)](https://postman.com)&nbsp;
[![IntelliJ](https://skillicons.dev/icons?i=idea)](https://www.jetbrains.com/idea)&nbsp;
[![VSCode](https://skillicons.dev/icons?i=vscode)](https://code.visualstudio.com)

</div>

---

## ◈ Backend Expertise

| Domain | Proficiency | Details |
|--------|:-----------:|---------|
| **Java & OOP** | ███████████░ | Core Java, Collections, Generics, Exception Handling, StringBuilder |
| **Spring Boot** | ██████████░░ | Layered Architecture, Auto-Configuration, REST Controllers, DTOs |
| **Spring Security** | █████████░░░ | Stateless JWT, OAuth2 (Google), Role-Based Access, Security Filter Chain |
| **JPA / Hibernate** | █████████░░░ | Entity Mapping, Relationships, JPQL, Pessimistic Locking, Lazy Loading |
| **REST API Design** | ██████████░░ | Resource Modeling, HTTP Semantics, Global Exception Handling |
| **MySQL** | ████████░░░░ | Schema Design, Joins, Transactions, ACID, Normalization, Indexing |
| **Docker** | ███████░░░░░ | Dockerfile, docker-compose, Multi-container orchestration |
| **Payment Integration** | ████████░░░░ | Razorpay Checkout, Webhooks, Idempotency, UPI Verification |

---

## ◈ Featured Projects

<details>
<summary><strong>ServeFlow — Smart Canteen Payment Verification & Token System</strong></summary>

<br/>

ServeFlow is a dual-portal canteen automation platform that solves the real-world problem of students reusing a single UPI payment screenshot to claim multiple food tokens. The core innovation is a payment matching engine that validates each Razorpay webhook event against pending bills using amount, time window, and UPI transaction ID — with an idempotency constraint at the database level to make duplicate redemption structurally impossible.

| Attribute | Detail |
|-----------|--------|
| **Stack** | Java 17 · Spring Boot 3 · Spring Security · JWT · OAuth2 · JPA/Hibernate · MySQL · Razorpay · Docker |
| **Architecture** | Dual-portal: QuickBill (Biller, JWT-secured) · Campus Bite student portal (Google OAuth — `@sairamtap.edu.in` only) |
| **Security** | Pessimistic locking for concurrent payment matching · Unique constraint on UPI transaction IDs · Domain-restricted OAuth |
| **Payments** | Razorpay webhook-driven auto-match · Ambiguous match resolution via last-4-digits of UPI reference |
| **Hardware** | ESC/POS thermal printer integration via network socket for live token printing |
| **Repository** | [![ServeFlow](https://img.shields.io/badge/GitHub-Serve--Flow-7C3AED?style=flat-square&logo=github)](https://github.com/BibiAshik/Serve-Flow) |

The most challenging design decision was handling concurrent ambiguous payments — when two students pay the same amount within the same time window. Rather than rejecting one silently, the system surfaces the conflict to the biller and resolves it deterministically using the UPI reference suffix, preserving correctness without degrading user experience.

</details>

<details>
<summary><strong>Trust Ledger SaaS — Multi-Tenant Gold Loan Management Platform</strong></summary>

<br/>

Trust Ledger SaaS is a multi-tenant B2B platform built for local gold loan shops across India to replace paper registers with a fully digital loan management system. It implements a complete three-tier role hierarchy — Super Admin, Shop Owner, and Customer — each with scoped access and independent business logic.

| Attribute | Detail |
|-----------|--------|
| **Stack** | Java 17 · Spring Boot 3.2.5 · Spring Security · JWT · JPA/Hibernate · MySQL 8 · Razorpay · iText 7 · Docker |
| **Multi-Tenancy** | Each shop operates in full data isolation; Super Admin has cross-tenant oversight |
| **Scale** | Subscription tiers: Basic (100 customers, ₹299/mo) · Pro (unlimited, ₹699/mo) |
| **Payments** | Razorpay Checkout + Razorpay Route for pro-tier online payment collection |
| **Features** | Loan lifecycle management · KYC (Aadhaar/PAN) · Automated email/SMS reminders · PDF receipt generation |
| **Repository** | [![TrustLedger SaaS](https://img.shields.io/badge/GitHub-TrustLedger--SaaS-5B21B6?style=flat-square&logo=github)](https://github.com/BibiAshik/TrustLedger-SaaS) |

Key architectural considerations included designing a clean subscription gate that enforces feature limits at the service layer rather than the UI, and building a reminder engine that triggers at day 1, 7, 15, and 30 overdue — resilient to application restarts.

</details>

<details>
<summary><strong>Trust Ledger — Gold Loan Portal (v1)</strong></summary>

<br/>

The original single-tenant Trust Ledger is a standalone gold loan management portal — the foundation that evolved into the SaaS version above. It focused on establishing the core domain model: loans, customers, interest calculations, and role-based access control using Spring Security with session-based authentication.

| Attribute | Detail |
|-----------|--------|
| **Stack** | Java · Spring Boot 3.5 · Spring Security · Spring Session JDBC · JPA/Hibernate · MySQL · H2 (dev) · Docker |
| **Security** | Form-based login · Spring Session with JDBC persistence · Role-scoped endpoint protection |
| **Core Domain** | Loan lifecycle (create, track, close, extend, seize) · Interest calculation engine · Customer KYC |
| **Repository** | [![Trust Ledger](https://img.shields.io/badge/GitHub-Trust--Ledger-4C1D95?style=flat-square&logo=github)](https://github.com/BibiAshik/Trust-Ledger) |

This project established the architectural patterns — controller → service → repository layering, custom exception handlers, DTO separation — that were carried forward and refined in every subsequent project.

</details>

<details>
<summary><strong>Campus Bite — Canteen Pre-Order Portal (v1)</strong></summary>

<br/>

Campus Bite is the first iteration of a college canteen management system, built as an end-to-end full-stack application with a clear two-role model: students browse and order without authentication, while admins manage the menu and order lifecycle through a secured dashboard.

| Attribute | Detail |
|-----------|--------|
| **Stack** | Java 21 · Spring Boot · Spring Security · Spring Data JPA · MySQL · Vanilla HTML/CSS/JS |
| **Auth** | Admin portal secured via Spring Security form login · Student flow is fully public |
| **Features** | Menu browsing with category filters · Cart (localStorage) · Token-based order pickup · Real-time order status updates |
| **Repository** | [![Campus Bite](https://img.shields.io/badge/GitHub-Campus--Bite-6D28D9?style=flat-square&logo=github)](https://github.com/BibiAshik/Campus-Bite) |

This project was the starting point — intentionally scoped to prove the full request lifecycle from browser to database and back, before tackling authentication complexity in later projects.

</details>

---

## ◈ Experience

**Backend Development Intern** — Srishti Innovative Educational Services
`2025`

Contributed to backend development tasks during an internship that served as the practical entry point into software engineering. Worked with web application components and gained hands-on exposure to the server-side development cycle — an experience that directly motivated the self-directed learning path that followed.

`Java` `Spring Boot` `Backend Development` `REST APIs` `Web Development`

---

## ◈ Achievements

<div align="center">

| Recognition | Details |
|:-----------:|:-------:|
| **3 Production-Grade Projects** | Built independently without formal training — Trust Ledger, Campus Bite, ServeFlow |
| **Self-Taught Backend Engineer** | Transitioned from ECE to backend development through structured self-learning |
| **Payment Systems** | Integrated Razorpay in two projects including webhook-driven real-time payment verification |
| **Security Architecture** | Implemented JWT, OAuth2, pessimistic locking, and idempotency from scratch |
| **Containerization** | Dockerized all major projects with production-ready Dockerfile and docker-compose configs |
| **B.E. Graduate 2026** | Electronics & Communication Engineering — Sri Sairam Institute of Technology, Chennai |

</div>

---

## ◈ Coding Profiles

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-BibiAshik-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/BibiAshik)
[![GeeksForGeeks](https://img.shields.io/badge/GeeksforGeeks-BibiAshik-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://www.geeksforgeeks.org/user/BibiAshik)
[![HackerRank](https://img.shields.io/badge/HackerRank-BibiAshik-00EA64?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/BibiAshik)

</div>

---

## ◈ GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=BibiAshik&show_icons=true&theme=midnight-purple&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D0D1A&title_color=A78BFA&icon_color=7C3AED&text_color=C4B5FD" />
&nbsp;&nbsp;
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BibiAshik&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0D0D1A&title_color=A78BFA&text_color=C4B5FD&langs_count=8" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=BibiAshik&theme=midnight-purple&hide_border=true&background=0D0D1A&ring=7C3AED&fire=A78BFA&currStreakLabel=C4B5FD&sideLabels=C4B5FD&sideNums=A78BFA&currStreakNum=ffffff&dates=6B7280" />

</div>

---

## ◈ GitHub Trophies

<div align="center">

[![Trophies](https://github-profile-trophy.vercel.app/?username=BibiAshik&theme=darkhub&no-frame=true&no-bg=true&margin-w=8&column=7)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## ◈ Contribution Activity

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=BibiAshik&theme=react-dark&bg_color=0D0D1A&color=A78BFA&line=7C3AED&point=C4B5FD&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## ◈ Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/BibiAshik/BibiAshik/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/BibiAshik/BibiAshik/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/BibiAshik/BibiAshik/output/github-snake-dark.svg" />
</picture>

</div>

---

## ◈ Current Focus

```yaml
learning:
  - Java 8 Features: Lambda, Streams, Optional, Method References
  - DSA: Arrays complete → Strings in progress
  - JPA Deep Dive: Advanced Hibernate, Query Optimization

building:
  - Portfolio polish: README upgrades, GitHub profile
  - Interview preparation: TCS NQT, Infosys InfyTQ, Wipro Elite

exploring:
  - Pagination & Sorting in Spring Data JPA
  - Builder pattern in Spring Boot services

open_to:
  - Java Backend Developer (Fresher)
  - Full-Stack Developer (Spring Boot + JS)
  - Service companies: TCS, Infosys, Wipro
  - Product startups based in India
```

---

## ◈ Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Bibi%20Ashik%20B%20A-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bibiashik05)
[![GitHub](https://img.shields.io/badge/GitHub-BibiAshik-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BibiAshik)
[![Email](https://img.shields.io/badge/Gmail-bibiashik05%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bibiashik05@gmail.com)

</div>

---

<div align="center">

*"I don't memorize solutions — I understand problems. The code follows."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,19,20,21,24&height=120&section=footer&animation=fadeIn" />

</div>
