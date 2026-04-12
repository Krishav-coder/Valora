# Valora

Valora is a frontend-focused e-commerce interface inspired by Amazon. The project is being built as a scalable UI practice exercise, with an emphasis on layout structure, reusable styling, and marketplace-style page composition using standard web technologies.

## Description

This project recreates the core visual experience of a modern online storefront, starting with an Amazon-like homepage and an in-progress cart page. It is intended as a portfolio-quality frontend build that demonstrates component-oriented styling, organized asset management, and a foundation for future interactive and backend-driven features.

## Features

- Amazon-inspired homepage layout
- Multi-section navigation bar with search UI
- Promotional hero/banner area
- Category and product-style content cards
- Horizontal deal and recommendation sections
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
|   `-- Cart.html
|-- styles/
|   |-- layout.css
|   |-- components.css
|   |-- main.css
|   `-- pages/
|       `-- cart.css
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
4. Open `pages/Cart.html` to review the current cart page layout.

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
