### Trương Tấn Khánh

**Project Lead · Full-stack Engineer** — building production software since 2018, from mobile and marketplace integrations to real-time command-center platforms.

I take systems from requirements to production: architecture, ticket-level planning, documentation that stands up to client review, and hands-on implementation of the hardest parts. Today I lead the engineering of operations platforms for clients in Singapore — NestJS backends, React and Angular frontends, IoT and live-video integrations.

---

### 🧭 Experience

#### Surbana Jurong — Project Lead (Full-stack) · _Apr 2024 – Present_

**Unified Command System** — command-center portal for island-wide operations in Singapore: an operator console plus a 3-projector video wall showing live cameras, maps and incidents.

- Designed the monorepo architecture (pnpm + Turborepo): **2 apps and 9 shared packages**
- Broke the full scope into **44 implementation-ready tickets** across every feature epic, cross-checked against Figma
- Designed the camera streaming layer (ONVIF / RTSP via MediaMTX) behind an adapter interface — mock and production sources switch by configuration
- Set the key technical decisions: OneMap-based 2D maps (MapLibre, deck.gl), Entra ID SSO with an in-app role/permission model, single on-prem Docker Compose deployment
- Lead a team of developers and build the operator-view app hands-on

**IoT building-management platform** — backend that processes and serves IoT data for an automated building-management system.

- Primary developer of core IoT data processing and provisioning features (Node.js, TypeORM, PostgreSQL)
- Shipped services as Docker images to AWS ECR, running on Kubernetes; reviewed the team's code and tests

**AI-assisted engineering workflow** — designed and maintain a standard set of Claude Code pipelines (scan → plan → apply → verify) used daily across NestJS, Angular and React codebases: diff-scoped self-review, API docs + OpenAPI generation with drift detection, test and lint scaffolding, and the ticket-driven pipeline that delivered the command-center monorepo.

#### NewIT Vietnam — Backend Developer · _Jul 2020 – Feb 2024_

Built and ran cross-border e-commerce integrations that continuously source and list products on Tmall, eBay US, Mercari, 95Point and Yahoo Shopping.

- **Brandtmall (3 years):** built AWS ECS sync services keeping Tmall listings live (S3, DynamoDB, AWS Translate); in phase 2, **led the migration from JavaScript to TypeScript microservices** on MySQL and owned image processing
- **Sole core developer** of an eBay US listing service and **core developer** of a 95Point integration — owning staging and production releases end to end
- **Primary developer** of the Mercari integration and developer / code reviewer on the Yahoo Shopping integration (TypeScript, AWS CDK, RDS, TypeORM)
- Proposed, built and operated an internal serverless tool (API Gateway, React, CloudFront) replacing direct S3 file edits with controlled, auditable updates

#### Earlier

- **AMIT Group** — Web Developer · _Mar 2020 – Jun 2020_ — Web APIs with ASP.NET Core / EF Core and Angular UI for an AI-driven web platform
- **HHD Group** — Mobile Developer · _Dec 2018 – Feb 2020_ — React Native apps integrated with the company ERP system

---

### 🧰 Stack

**Backend** &nbsp; ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![TypeORM](https://img.shields.io/badge/TypeORM-FE0803?style=flat-square&logo=typeorm&logoColor=white)

**Frontend** &nbsp; ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white) ![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white)

**Data** &nbsp; ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)

**Cloud & Infra** &nbsp; ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

---

### 📐 Principles I lead by

- **Design is written down.** Architecture decisions and tickets are documented and reviewed before code is written.
- **Simple scales.** Framework-native solutions first; every new tool has to earn its place.
- **Standards are a team asset.** Shared conventions and automated review let a small team move fast across many repositories.
- **Leads still ship.** I stay in the code, because good technical decisions come from knowing where the real complexity lives.

---

### 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/truongtankhanh/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ttkhanh100896@gmail.com)

📍 Vietnam · Open to conversations on technical leadership and full-stack architecture
