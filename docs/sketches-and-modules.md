# Sketches & Modules

## 1. Overview

Archimedes follows a modular architecture designed to adapt to different business segments and operational requirements.

The platform is organized around two independent concepts:

- **Sketches:** Business-specific foundations.
- **Modules:** Optional functionality that extends business operations.

The objective is to provide flexibility without forcing businesses to purchase or use unnecessary features.

## 2. Sketches

A Sketch represents a business segment within Archimedes.

Each Sketch provides a foundation adapted to the operational characteristics of its respective business type.

Examples:

| Sketch | Business segment |
|---|---|
| Confectionery | Cakes, sweets and custom orders |
| Bakery | Bread, baked goods and production |
| Snack Bar | Food orders and quick service |
| Mobile Phone Retail | Electronics and device sales |
| Supermarket | Retail and inventory operations |
| Manicure | Beauty services and appointments |

Sketches define the business-specific experience and operational requirements.

## 3. Modules

Modules are independent functional components that businesses can optionally activate.

Examples:

- Inventory management
- Employee management
- Suppliers and purchasing
- Order printing
- Scale integration
- Scheduling and appointments
- Customer relationship management (CRM)

Modules should be designed to work independently whenever their functionality permits.

No module should be mandatory simply because a business selected a particular Sketch.

## 4. Business Registration Flow

The intended onboarding process is:

1. Business owner creates an account.
2. Owner selects the appropriate Sketch.
3. Owner reviews the available modules.
4. Owner selects the modules required by the business.
5. Platform configures the business environment according to those selections.

## 5. Design Principles

The architecture should follow these principles:

- Modularity: Features should be separated into independent components.
- Flexibility: Businesses should choose their own functionality.
- Independence: Modules should not create unnecessary dependencies.
- Scalability: New Sketches and modules should be introduced without redesigning the entire platform.
- Adaptability: Business-specific rules should be configurable where appropriate.

## 6. Future Direction

The long-term vision includes:

- Additional business Sketches.
- Custom Sketch development.
- Reusable modules across different business segments.
- Multiple business units.
- Flexible module activation and commercial plans.

---

*This document describes the product vision and architectural principles. Implementation details may evolve during development.*
