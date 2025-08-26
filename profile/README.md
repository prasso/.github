# Faxt - Multi-Tenant SaaS Platform
**Faxt** (formerly Prasso) is a powerful multi-tenant Laravel framework designed for building and hosting Software-as-a-Service applications with ease.

## Overview
Faxt is an open-source platform that enables developers to create scalable multi-tenant SaaS applications using Laravel. Originally developed as Prasso, our platform now operates under the faxt.com domain and focuses on providing a robust foundation for multi-site hosting and plugin-based extensibility.

## Key Features
- **Multi-Tenant Architecture**: Host multiple independent applications on a single codebase with complete data isolation
- **Laravel Plugin System**: Extend functionality through modular Laravel packages and plugins
- **SaaS-Ready Foundation**: Built-in tenant management, billing integration, and subscription handling
- **Admin Panel Integration**: Powered by Filament for intuitive administration across all tenants
- **API-First Design**: RESTful APIs for seamless integration with mobile apps and third-party services
- **Low-Code Configuration**: Deploy new tenant sites with minimal custom development

## Multi-Tenant SaaS Capabilities
- **Tenant Isolation**: Complete separation of data, configurations, and customizations per tenant
- **Dynamic Subdomain/Domain Routing**: Support for custom domains and automated subdomain provisioning
- **Scalable Plugin Architecture**: Add features through Laravel packages without affecting other tenants
- **Centralized Management**: Single dashboard to manage multiple client applications
- **Individual Site Hosting**: Each tenant can operate as an independent website with custom branding

## How It Works for SaaS Providers
1. **Setup**: Deploy the Faxt platform on your infrastructure
2. **Configure**: Set up multi-tenancy settings and base plugins
3. **Onboard Tenants**: Create new tenant instances with custom configurations
4. **Extend**: Add functionality through Laravel packages and custom plugins
5. **Scale**: Grow your SaaS offering with automatic tenant provisioning

## How It Works for Developers
1. **Clone**: Start with the [prasso_api repository](https://github.com/prasso/prasso_api)
2. **Configure**: Set up multi-tenant database connections and routing
3. **Develop**: Create Laravel packages and plugins for extended functionality
4. **Deploy**: Launch tenant sites with customized features
5. **Maintain**: Manage updates and features across all tenant instances

## Plugin Development
Faxt encourages a plugin-based architecture where functionality can be added through Laravel packages:
- Create reusable components across multiple tenants
- Maintain clean separation of core platform and custom features
- Enable/disable features per tenant as needed
- Distribute plugins to other Faxt installations

## Migration from Prasso.io
We've transitioned from prasso.io to faxt.com to provide better long-term sustainability and focus on our multi-tenant SaaS capabilities. Existing installations will continue to work, and migration guides are available for updating domain references.

## Contributing
We welcome contributions to the Faxt ecosystem:
- Core platform improvements
- New plugin packages
- Documentation enhancements
- Bug fixes and performance optimizations

See our [Contribution Guidelines](https://github.com/prasso/prasso_api/blob/master/docs/contributing.md) for more details.

## License
Faxt is licensed under the [MIT License](LICENSE.md).

## Support
For technical support, business inquiries, or partnership opportunities:
- Email: [info@faxt.com](mailto:info@faxt.com)
- Documentation: Visit our GitHub repositories for detailed setup guides
- Community: Join discussions in our GitHub issues and discussions

---
*Building scalable SaaS solutions with Laravel made simple.*
