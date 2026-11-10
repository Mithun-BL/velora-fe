<!-- # React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type-aware lint rules:

```js
export default defineConfig([
  globalIgnores(['dist']),
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      // Other configs...

      // Remove tseslint.configs.recommended and replace with this
      tseslint.configs.recommendedTypeChecked,
      // Alternatively, use this for stricter rules
      tseslint.configs.strictTypeChecked,
      // Optionally, add this for stylistic rules
      tseslint.configs.stylisticTypeChecked,

      // Other configs...
    ],
    languageOptions: {
      parserOptions: {
        project: ['./tsconfig.node.json', './tsconfig.app.json'],
        tsconfigRootDir: import.meta.dirname,
      },
      // other options...
    },
  },
])

```

You can also install [eslint-plugin-react-x](https://npmx.dev/package/eslint-plugin-react-x) and [eslint-plugin-react-dom](https://npmx.dev/package/eslint-plugin-react-dom) for React-specific lint rules:

```js
// eslint.config.js
import reactX from 'eslint-plugin-react-x'
import reactDom from 'eslint-plugin-react-dom'

export default defineConfig([
  globalIgnores(['dist']),
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      // Other configs...
      // Enable lint rules for React
      reactX.configs['recommended-typescript'],
      // Enable lint rules for React DOM
      reactDom.configs.recommended,
    ],
    languageOptions: {
      parserOptions: {
        project: ['./tsconfig.node.json', './tsconfig.app.json'],
        tsconfigRootDir: import.meta.dirname,
      },
      // other options...
    },
  },
])

``` -->
# VELORA-FE

**VELORA – Style Beyond Seasons**

A premium fashion e-commerce frontend built with React.js, TypeScript, and Tailwind CSS, delivering a modern and seamless shopping experience.

## Tech Stack

- React.js
- Vite
- TypeScript
- Tailwind CSS v4
- React Router DOM
- Redux Toolkit
- Axios
- React Hook Form
- Zod
- Lucide React

## Project Setup & Configuration

- Initialized React.js application using Vite.
- Configured TypeScript for type-safe development.
- Integrated Tailwind CSS v4 for utility-first styling.
- Configured React Router for application navigation.
- Added Redux Toolkit for global state management.
- Configured Axios for backend API integration.
- Integrated React Hook Form and Zod for form handling and validation.
- Added Lucide React for icons.
- Established a scalable and reusable folder structure.

## Project Architecture

```text
src/
├── assets/
├── components/
│   ├── common/
│   ├── layout/
│   └── ui/
├── pages/
├── layouts/
├── hooks/
├── services/
├── store/
├── types/
├── utils/
├── styles/
├── App.tsx
└── main.tsx

public/
├── images/
│   ├── banners/
│   ├── products/
│   ├── categories/
│   └── collections/
├── icons/
└── fonts/
```

## Planned Features

- Premium fashion homepage
- Responsive navigation and mega menu
- Product listing and category pages
- Product search and filtering
- Product details
- Shopping cart
- Wishlist
- User authentication
- Checkout experience
- Order history
- Responsive design for mobile, tablet and desktop

## Getting Started

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Navigate to the project

```bash
cd velora-fe
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start development server

```bash
npm run dev
```

### 5. Build for production

```bash
npm run build
```

## Backend Integration

The frontend communicates with the VELORA backend API (`velora-be`) for authentication, product data, cart management, wishlists and order processing.

## Project Status

Frontend initialization and foundational project configuration completed. Feature development is in progress.

---

**VELORA – Style Beyond Seasons**