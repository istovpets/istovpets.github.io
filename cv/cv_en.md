# Igor Alexandrovich Stovpets

**Backend Senior Go Developer**

<div style="display:flex; align-items:flex-start;">
  <img src="avatar.jpg" style="height:130px; margin-right:16px;">
  <div>
    <strong>email:</strong> igor@stovpets.com<br>
    <strong>telegram:</strong> <a href="https://t.me/istovpets">@istovpets</a><br>
    <strong>tel:</strong> +90 5380839471, +7 9037851649<br>
    <strong>portfolio:</strong>
    <a href="https://programmer.stovpets.com">programmer.stovpets.com</a>
  </div>
</div>

## Professional Skills

- Golang programming — 5 years
- Delphi programming — 25 years
  
### Experience with the following systems/technologies
- Teamwork with Git. Code review.
- DBMS — PostgreSQL, CockroachDB, MS SQL
- NoSQL databases — Redis
- Message brokers — NATS
- Containerization systems — Docker, Docker Compose
- Metrics collection and visualization systems — Prometheus, Grafana
- OpenAPI, Swagger
- CI/CD — GitLab
- Jira, Confluence

## Work Experience

### October 2025 — Present

**Cleeme. Backend Senior Go Developer**

Backend of a service for a company providing cleaning services

- Selection of an order executor by region using the DaData.ru REST API
- Subsystem for performer ratings and reviews
- Subsystem for working with S3 file storage
- Subsystem for generating PDF documents from templates
- Face recognition subsystem in photos
- Text recognition subsystem in documents (OCR)
- REST API endpoints

### July 2024 — October 2025

**Twinby. Backend Middle Go Developer**

Decomposition of a monolith into microservices

- Email and push mailing management microservice. Template-based campaign creation, scheduled sending. CockroachDB, NATS, REST HTTP API, Swagger.
- Data synchronization microservice with the monolith. Retrieving user data from the monolith database. CockroachDB, NATS, Redis.
- Email and push notification sending microservice. SMTP2GO API, SMTP, Firebase, NATS, rate limiting.
- Cloud storage microservice based on S3. File upload and download to cloud storage. REST HTTP API, AWS S3 SDK.

### 2021 — 2024

**1C-Rarus. Go Developer**

- Project "Simple Electronic Signature". Architecture design, implementation, testing, deployment.  
  The service allows registered clients to upload contract documents into the system and remotely sign them by counterparties using one-time passwords sent via SMS.  
  The application consists of two services: the Signature Service and the Data Exchange Service with the accounting system.  
  The application uses PostgreSQL DBMS, integration with S3 file storage, interaction with the SMS4B SMS delivery service, email notifications, and PDF document editing.  
  Used packages/libraries: AWS SDK for Go, pdfcpu (a Go PDF processor), otp (One-Time Password utilities for Go), pgx.
- Project "Proxy Server for Publishing 1C Databases". Architecture design, implementation, testing, deployment.  
  Developed a reverse proxy server for publishing company product services built on the 1C:Enterprise platform.  
  The service allows forwarding external HTTP and SOAP service calls written in 1C through NAT into a local network.  
  The application consists of three services: the Proxy Service, the WireGuard VPN Management Service, and the Data Exchange Service with the accounting system.  
  The application uses PostgreSQL DBMS.  
  Used packages/libraries: wireguard, wgctrl, pgx, netlink.

### 2001 — 2021

**1C-Rarus. Software Engineer**

- Development of retail equipment drivers for the 1C platform. Delphi, C++.
- Development of desktop applications for Windows. Delphi.
- Development and support of mobile applications for Android. Java, Kotlin.
