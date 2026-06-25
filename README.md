# Valora

Valora is a frontend-focused e-commerce interface built as a scalable UI practice exercise. The project emphasizes layout structure, reusable styling, and marketplace-style page composition using standard web technologies.

## Description

This project recreates the core visual experience of a modern online storefront, starting with a Valora-branded homepage and a growing set of connected content pages. It is intended as a portfolio-quality frontend build that demonstrates component-oriented styling, organized asset management, and a foundation for future interactive and backend-driven features.

## Features

- Valora-branded homepage layout
- Multi-section navigation bar with search UI
- Promotional hero/banner area
- Category and product-style content cards
- Horizontal deal and recommendation sections
- Connected gift card, customer service, digital services, fraud prevention, registry, and gift request pages
- Dedicated Valora gift card page and customer care support hub
- Shared top navigation across the main pages
- Footer modeled after large e-commerce platforms
- Dedicated cart page structure
- Modular CSS organization for layout, shared components, and page-specific styling

## Tech Stack

- HTML5
- CSS3

## Project Structure

```text
Valora/
|-- index.html
|-- README.md
|-- pages/
|   |-- Cart.html
|   |-- Customer-Care-Digital-Services.html
|   |-- Customer_Service.html
|   |-- customer-service.html
|   |-- Fraud-prevention.html
|   |-- Gift-card.html
|   |-- Gift-request.html
|   |-- Registry.html
|   |-- Special-Gift-cards.html
|   `-- Valora-gift-card.html
|-- styles/
|   |-- layout.css
|   |-- components.css
|   |-- main.css
|   `-- pages/
|       |-- cart.css
|       |-- customer-care-digital-services.css
|       |-- customer-service.css
|       |-- fraud-prevention.css
|       |-- gift-card.css
|       |-- gift-request.css
|       |-- registry.css
|       |-- special-gift-cards.css
|       `-- valora-gift-card.css
|-- assets/
|   |-- images/
|   |-- icons/
|   `-- fonts/
|-- data/
|   `-- products.json
`-- scripts/
    `-- main.js
```

## Setup Instructions

1. Clone the repository.
2. Open the project folder in your editor.
3. Launch `index.html` in a browser to view the homepage.
4. Use the shared navigation to move between the cart, customer service, digital services, gift cards, fraud prevention, registry, and gift request pages.

For the best development workflow, use a local static server such as VS Code Live Server.

## Current Limitations

- No backend or database integration
- No authentication, checkout, or real cart logic
- Product interactions are not fully functional yet
- Cart page is only partially implemented
- Responsiveness is still limited and needs refinement

## Future Improvements

- Improve mobile and tablet responsiveness
- Add JavaScript-driven interactions for search, cart, and navigation
- Connect product data dynamically to the UI
- Build out full cart, product detail, and checkout flows
- Introduce backend services for user, cart, and order management

## Author

Tarun Parihar
