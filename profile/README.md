# Faxt - Multi-Tenant SaaS Platform

**Faxt** (formerly Prasso) is a powerful multi-tenant framework designed for building and hosting Software-as-a-Service applications with framework flexibility.

## Overview

Faxt is an open-source platform that enables developers to create scalable multi-tenant SaaS applications using Laravel, React, or both. Originally developed as Prasso, our platform now operates under the faxt.com domain and focuses on providing a robust foundation for multi-site hosting and modular extensibility with your preferred technology stack.

## Key Features

- **Multi-Tenant Architecture**: Host multiple independent applications on a single codebase with complete data isolation
- **Framework-Flexible Design**: Build with Laravel backend, React frontend, or integrate both seamlessly
- **Modular Plugin System**: Extend functionality through modular packages and components
- **SaaS-Ready Foundation**: Built-in tenant management, billing integration, and subscription handling
- **Modern Admin Interface**: Intuitive administration across all tenants with powerful dashboard capabilities
- **API-First Design**: RESTful APIs for seamless integration with mobile apps, SPAs, and third-party services
- **Low-Code Configuration**: Deploy new tenant sites with minimal custom development

## Multi-Tenant SaaS Capabilities

- **Tenant Isolation**: Complete separation of data, configurations, and customizations per tenant
- **Dynamic Subdomain/Domain Routing**: Support for custom domains and automated subdomain provisioning
- **Scalable Architecture**: Add features through modular packages without affecting other tenants
- **Centralized Management**: Single dashboard to manage multiple client applications
- **Individual Site Hosting**: Each tenant can operate as an independent website with custom branding
- **Technology Stack Choice**: Deploy tenants with Laravel, React, or full-stack configurations

## Technology Stack

### Backend
- **Laravel Framework**: Robust PHP backend with multi-tenancy support
- **RESTful API**: Well-documented API endpoints for all platform features
- **Database Isolation**: Tenant-specific databases or schema-based isolation

### Frontend
- **React Support**: Build modern, interactive user interfaces
- **Laravel Blade**: Traditional server-side rendering option
- **Flexible Integration**: Mix and match based on project requirements

### Additional Technologies
- **Filament Admin**: Optional admin panel integration
- **Queue Management**: Background job processing for scalability
- **Cache Layer**: Redis/Memcached support for performance

## How It Works for SaaS Providers

1. **Setup**: Deploy the Faxt platform on your infrastructure with multi-tenancy configurations
2. **Configure**: Set up database connections, routing, and choose your technology stack
3. **Onboard Tenants**: Create new tenant instances with custom configurations
4. **Extend**: Add functionality through Laravel packages, React components, or both
5. **Scale**: Grow your SaaS offering with automatic tenant provisioning and updates

## How It Works for Developers

1. **Clone**: Start with the [prasso_api repository](https://github.com/prasso/prasso_api)
2. **Configure**: Set up multi-tenant database connections and routing
3. **Choose Stack**: Decide on Laravel-only, React-only, or full-stack approach
4. **Develop**: Create packages, components, and plugins for extended functionality
5. **Deploy**: Launch tenant sites with customized features
6. **Maintain**: Manage updates and features across all tenant instances

## Plugin & Component Development

Faxt encourages a modular architecture where functionality can be added through packages and components:

- Create reusable Laravel packages for backend functionality
- Build React components for rich frontend experiences
- Maintain clean separation of core platform and custom features
- Enable/disable features per tenant as needed
- Distribute plugins and components to other Faxt installations
- Mix backend and frontend modules based on requirements

## Use Cases

Faxt is ideal for building SaaS solutions across various industries:

- **Accounting & Financial Services**: Multi-tenant accounting platforms
- **Salons & Spas**: Appointment and client management systems
- **Automotive Services**: Shop management and inventory tracking
- **Retail & Resale**: Point-of-sale and inventory systems
- **Real Estate**: Property management and listing platforms
- **Manufacturing**: ERP solutions for production and order management

## Migration from Prasso.io

We've transitioned from prasso.io to faxt.com to provide better long-term sustainability and focus on our multi-tenant SaaS capabilities. Existing installations will continue to work, and migration guides are available for updating domain references.

## Getting Started

### Prerequisites
- PHP 8.1 or higher
- Composer
- Node.js & NPM (for React development)
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
```

## Contributing

We welcome contributions to the Faxt ecosystem:

- Core platform improvements
- New plugin packages and React components
- Documentation enhancements
- Bug fixes and performance optimizations
- Framework integration improvements

See our [Contribution Guidelines](https://github.com/prasso/prasso_api/blob/master/docs/contributing.md) for more details.

## Documentation

- **Setup Guide**: Detailed installation and configuration instructions
- **Multi-Tenancy Guide**: Implementing and managing tenants
- **Plugin Development**: Creating Laravel packages for Faxt
- **Component Development**: Building React components for tenant frontends
- **API Reference**: Complete API documentation
- **Deployment Guide**: Production deployment best practices

## Community & Support

For technical support, business inquiries, or partnership opportunities:

- **Email**: [info@faxt.com](mailto:info@faxt.com)
- **Documentation**: Visit our GitHub repositories for detailed setup guides
- **Issues**: Report bugs and request features via GitHub Issues
- **Discussions**: Join conversations in GitHub Discussions

## Repositories

- **Main Platform**: [prasso_api](https://github.com/prasso/prasso_api)
- **Spa & Salon Package**: [faxt-development/Spa-and-Salon](https://github.com/faxt-development/Spa-and-Salon)
- **Additional Plugins**: Coming soon

## License

Faxt is licensed under the [MIT License](LICENSE.md).

## Acknowledgments

Built with ❤️ by the Faxt team and contributors. Special thanks to the Laravel and React communities for their excellent frameworks and tools.

---

*Building scalable multi-tenant SaaS solutions made simple - with the flexibility to choose your technology stack.*
