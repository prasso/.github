# Faxt — Multi‑Tenant SaaS Platform (formerly Prasso)

**Faxt** is an open‑source, multi‑tenant platform for building and hosting SaaS applications with framework flexibility. It provides a robust foundation for multi‑site hosting, modular extensibility, and API‑driven development using Laravel, React, or both.

---

## Overview

Faxt (previously Prasso) powers scalable multi‑tenant SaaS apps with a flexible architecture that supports modern web and mobile experiences. It runs under the **faxt.com** domain and focuses on rapid tenant provisioning, modular packages, and an API‑first backend.

---

## Key Features

- **Multi‑Tenant Architecture** — Host multiple apps on one codebase with full data isolation  
- **Framework‑Flexible** — Laravel backend, React frontend, or full‑stack integration  
- **Modular Plugin System** — Extend via packages and components  
- **SaaS‑Ready** — Tenant management, billing integration, subscription handling  
- **Modern Admin Interface** — Centralized dashboards and tenant tooling  
- **API‑First** — RESTful APIs for mobile, SPA, and third‑party integrations  
- **Low‑Code Configuration** — Deploy new tenant sites quickly with minimal dev work  

---

## Multi‑Tenant SaaS Capabilities

- **Tenant Isolation** — Separate data, config, and customizations per tenant  
- **Dynamic Domain Routing** — Custom domains + automated subdomains  
- **Scalable Architecture** — Add modules without impacting other tenants  
- **Centralized Management** — One dashboard for multiple client apps  
- **Independent Site Hosting** — Custom branding per tenant  
- **Stack Choice** — Laravel‑only, React‑only, or full‑stack  

---

## Technology Stack

### Backend
- **Laravel** — Robust PHP backend with multi‑tenancy support  
- **REST APIs** — Documented endpoints for all platform features  
- **Database Isolation** — Tenant‑specific DBs or schema‑based separation  

### Frontend
- **React** — Modern SPA experiences  
- **Laravel Blade** — Server‑rendered pages  
- **Flexible Integration** — Mix and match as needed  

### Additional
- **Filament Admin** (optional)  
- **Queues** for background jobs  
- **Redis/Memcached** for caching  

---

## How It Works (SaaS Providers)

1. **Setup** — Deploy Faxt on your infrastructure  
2. **Configure** — DB connections, routing, and stack choices  
3. **Onboard Tenants** — Create tenant instances with custom config  
4. **Extend** — Add packages/components as needed  
5. **Scale** — Automate tenant provisioning and updates  

---

## How It Works (Developers)

1. **Clone** — [prasso_api](https://github.com/prasso/prasso_api)  
2. **Configure** — Multi‑tenant DB + routing  
3. **Choose Stack** — Laravel, React, or full‑stack  
4. **Develop** — Packages, components, plugins  
5. **Deploy** — Launch tenant sites  
6. **Maintain** — Roll out updates across tenants  

---

## Plugin & Component Development

Faxt is built for modular development:

- Build reusable Laravel packages  
- Create React components for rich UI  
- Keep core vs custom features cleanly separated  
- Enable/disable features per tenant  
- Share plugins across Faxt installations  

---

## Use Cases

- **Accounting & Finance**  
- **Salons & Spas**  
- **Automotive Services**  
- **Retail & Resale**  
- **Real Estate**  
- **Manufacturing / ERP**  

---

## Migration from Prasso.io

Faxt has transitioned from **prasso.io** to **faxt.com** for long‑term sustainability. Existing installations continue to work, and migration guides are available for domain updates.

---

## Getting Started

### Prerequisites
- PHP 8.1+  
- Composer  
- Node.js & npm (for React)  
- MySQL/PostgreSQL  
- Redis (recommended)

### Quick Start

```bash
# Clone the repository
git clone https://github.com/prasso/prasso_api.git

# Install dependencies
composer install
npm install

# Configure environment
cp .env.example .env
php artisan key:generate

# Set up database
php artisan migrate
php artisan db:seed

# Start development server
php artisan serve
npm run dev

---

## Contributing

We welcome:

- Core platform improvements  
- Plugin packages & React components  
- Documentation updates  
- Bug fixes & performance work  

See [Contribution Guidelines](https://github.com/prasso/prasso_api/blob/master/docs/contributing.md).

---

## Documentation

- **Setup Guide**  
- **Multi‑Tenancy Guide**  
- **Plugin Development**  
- **Component Development**  
- **API Reference**  
- **Deployment Guide**  

---

## Community & Support

- **Email:** [info@faxt.com](mailto:info@faxt.com)  
- **Issues:** GitHub Issues  
- **Discussions:** GitHub Discussions  

---

## Repositories

- **Main Platform:** [prasso_api](https://github.com/prasso/prasso_api)  
- **Spa & Salon Package:** [faxt-development/Spa-and-Salon](https://github.com/faxt-development/Spa-and-Salon)  
- **Additional Plugins:** Coming soon  

---

## License

Faxt is licensed under the [MIT License](LICENSE.md).

---

*Build scalable multi‑tenant SaaS solutions with the freedom to choose your stack.*
