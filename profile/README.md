# 🚀 WizeWorks

**Composable APIs. Custom Content. One Platform.**

WizeWorks is an open, extensible content platform and headless CMS built for developers, creators, and businesses who want complete control over their content, APIs, and digital experiences — without sacrificing flexibility, scalability, or speed.

---

## 🌟 Key Features

### 🔧 Dynamic GraphQL API Generation
- Instantly generate GraphQL types, inputs, filters, and resolvers from simple JSON metadata.
- Nested relationships, array fields, enum handling, and pagination built-in.

### 🧱 MongoDB-first Flexibility
- Designed for flexible data modeling and content versioning with MongoDB.
- Auto-creates models and collections based on schema metadata.

### ⚙️ Developer-Centric Architecture
- Built with **Fastify**, **GraphQL**, **TypeScript**, and **Supabase**.
- Focused on performance, simplicity, and modular extensibility.

### 🔐 Secure by Design
- Role-based access policies with Supabase RLS.
- Environment-based configuration, token authentication support, and upcoming API key scoping.

### 🚀 GitHub Actions + AKS Native
- Deploy with confidence using container-based CI/CD pipelines to Azure Kubernetes Service (AKS).
- TLS certs handled by `cert-manager` and NGINX ingress with per-namespace issuers like `wizeworks-encrypt`.

---

## 🛠️ Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/wizeworks/wizeworks.git
cd wizeworks
