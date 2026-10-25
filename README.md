# Paradise Nursery

**Project name:** Paradise Nursery

Paradise Nursery is a React + Redux Toolkit shopping application for an online houseplant shop. Visitors land on a welcome page, browse plants grouped by category, add them to a shopping cart, and review or adjust their cart before checkout.

## Features

- Landing page with the company name, an About Us section and a "Get Started" button
- Product listing page with six houseplants in three categories (Air Purifying, Aromatic, Low Maintenance)
- "Add to Cart" button that becomes disabled once a plant is added
- Navbar cart icon showing the total number of items in the cart
- Shopping cart page with increase, decrease and delete controls
- Per-item subtotal and total cart amount
- "Continue Shopping" and "Checkout" buttons (Checkout shows a "Coming Soon" message)

## Tech Stack

- React 18
- Redux Toolkit and React Redux
- Vite

## Getting Started

```bash
npm install
npm run dev
```

Then open the local URL shown in the terminal.

## Project Structure

```
src/
  App.jsx          Landing page and view switching
  App.css          Styles, including the landing page background image
  AboutUs.jsx      Company description
  ProductList.jsx  Product listing page
  CartItem.jsx     Shopping cart page
  CartSlice.jsx    Redux slice: addItem, removeItem, updateQuantity
  store.js         Redux store
  main.jsx         App entry point
```
