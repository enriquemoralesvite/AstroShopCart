# AstroCart 🛒

A minimal shopping page built with **Astro**, featuring a fully functional cart component, persistent state, and a clean UI. This repo captures the last known working version of the cart (“canasta”) logic before a merge went awry—so you can pick up right where you left off.

---

## 🚀 What It Does

- **Product Listing**: Displays a list of products (static data or local assets).
- **Dynamic Cart**:  
  - Add, remove, and adjust quantities.  
  - Real-time subtotal and total calculations.  
  - “Empty cart” confirmation popup.  
- **Persistent State**: Cart contents stored in `localStorage` so your session survives reloads.
- **Responsive UI**: Built with Astro + basic CSS/Tailwind utility classes.

---

## 🗂️ Project Structure




```text
/
├── public/                # Static assets (images, icons)
├── src/
│   ├── components/        # CartPreview, ProductCard, Header, etc.
│   ├── layouts/           # Layout wrapper
│   ├── pages/
│   │   ├── index.astro    # Home / product list
│   │   └── canasta.astro  # Cart page (functional version)
│   └── styles/            # Global or component CSS
├── astro.config.mjs       # Astro configuration
└── package.json           # Scripts & dependencies


---

## 🧩 Key Components

- `Grilla.astro` – Product grid display  
- `CartPreview.astro` – Shopping cart preview  
- `Header.astro` – Navigation and cart controls  
- `Tarjeta.astro` – Product card component  

---

## ⚙️ Getting Started

1. Clone the repository
2. Install dependencies:

```bash
pnpm install

pnpm run dev
pnpm run build

```
👉 **[Live Demo](https://astro-shopcart.vercel.app/)**
