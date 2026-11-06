
# SooqFlow — Project Brief

Version: 0.1
Status: Draft

## 1. Business Problem

A small retailer in Jordan needs a web platform
to manage products, inventory, and customer orders.

## 2. Project Goal

Build an e-commerce storefront and an internal
store management dashboard.

## 3. Target Users

### Customer
- Browse available products
- Search and filter products
- View product details
- Add products to a cart
- Place a demo order

### Store Staff
- Manage product information
- Manage inventory
- Review customer orders
- Update order statuses

## 4. Functional Requirements

FR-01: Display available products.
FR-02: Display product details and prices in JOD.
FR-03: Allow product search and filtering.
FR-04: Allow customers to manage a shopping cart.
FR-05: Support simulated checkout.
FR-06: Allow authorized staff to manage products.
FR-07: Allow authorized staff to manage orders.
FR-08: Track inventory quantities.

## 5. Non-Functional Requirements

NFR-01: Responsive, mobile-first interface.
NFR-02: Accessible semantic HTML.
NFR-03: Server-side validation for trusted operations.
NFR-04: Staff-only access to administrative actions.
NFR-05: Automated tests for critical business rules.
NFR-06: Clear documentation and deployment instructions.

## 6. First User Story

US-01: Browse Products

As a customer,
I want to browse available products,
so that I can choose items to purchase.

### Acceptance Criteria

- Products have a name, price, and image.
- Prices display in JOD.
- Each product has a details link.
- The catalog works on mobile devices.
- Empty results show a useful message.

## 7. MVP Scope

- Product catalog
- Product details
- Search and filters
- Shopping cart
- Demo checkout
- Order management
- Inventory management

## 8. Out of Scope

- Real payment processing
- Multi-vendor marketplace
- Native mobile applications
- Real shipping-provider integrations

## 9. Initial Constraints

- Use synthetic product and customer data.
- Begin with HTML, CSS, and JavaScript.
- Introduce backend and database later.
- Preserve one evolving GitHub repository.
- No real financial transactions.

## 10. Project Status

Requirements documentation: In progress.
Implementation: Not started.
