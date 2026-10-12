# Full-stack e-commerce platform — collaborative project

**Repository:** [bouzidi48/projet](https://github.com/bouzidi48/projet) (team-owned, public)  
**Technology:** NestJS, TypeScript, React, Vite, TypeORM, MySQL; Stripe-related integration code.

## Product and system
An e-commerce application organized into three separate areas: a **NestJS backend**, a **React customer frontoffice**, and a **React backoffice**. The source tree contains modules for authentication, products, categories, product options, orders, payments, user management, reviews, and administration.

## My role
**System conception, software architecture and design-pattern responsibilities in the team.** I helped shape the application's overall technical structure and separation of responsibilities between the three parts.

## Architecture at a glance
```text
React customer storefront ------+
                                 +--> NestJS API --> business modules --> database
React administration backoffice -+
                                       |
                                       +--> payment integration components
```
The diagram is a conceptual interpretation of the repository layout, not a deployed infrastructure diagram.

## Relevant freelance work
Full-stack application planning, NestJS/TypeScript backend systems, React dashboards, API integration, modularization, and e-commerce maintenance.

**Attribution:** Collaborative work; repo owner is a teammate. Individual feature ownership, exact design-pattern choices, and production/payment readiness have not been independently established. These should not be presented as solely authored or production-verified by me.
