# Phone Catalog

A product catalog built with React and TypeScript. Browse phones, tablets, and accessories, explore product details, and manage your cart and favorites.

## Live Preview

[Open Phone Catalog](https://vadym-fe.github.io/phone-catalog/)

## Design Reference

[Figma — Original design](<https://www.figma.com/file/T5ttF21UnT6RRmCQQaZc6L/Phone-catalog-(V2)-Original>)

## Technologies Used

- React
- TypeScript
- React Router
- React Context API
- SCSS and CSS Modules
- Vite
- Fetch API

## Features

- Product categories: phones, tablets, and accessories
- Product sorting and pagination
- Product details pages
- Shopping cart
- Favorites
- Client-side navigation with React Router

## Product Data

Product information is loaded from JSON files in `public/api` using the Fetch API. Product images and fonts are stored in the `public` directory.

## Getting Started

### Requirements

Install Node.js and npm before running the project.

The project has been checked with Node.js 24.12.0.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Vadym-fe/phone-catalog.git
   ```

2. Navigate to the project folder:

   ```bash
   cd phone-catalog
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

Open the local URL displayed in the terminal.

## Available Commands

| Command | Description |
| --- | --- |
| `npm start` | Start the development server |
| `npx tsc --noEmit` | Check TypeScript types |
| `npm run lint` | Format the source code and run linters |
| `npm run build` | Create a production build |
| `npm run deploy` | Build and deploy the catalog to GitHub Pages |

## Project Structure

- `src/api` — functions for loading product data
- `src/context` — shared application state
- `src/modules` — pages and reusable components
- `src/types` — TypeScript types
- `public` — product data, images, fonts, and favicon
