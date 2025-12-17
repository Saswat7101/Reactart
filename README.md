# Styling Project

A React application focused on styling components using Tailwind CSS and styled-components.

## Description

This project is a React app built with Vite, featuring modern styling techniques with Tailwind CSS v4 and styled-components. It includes various UI components like Header, Button, Input, and AuthInputs, demonstrating different styling approaches.

## Features

- Modern React 19 setup
- Tailwind CSS v4 integration with Vite plugin
- Styled-components for component-level styling
- ESLint for code quality
- Hot module replacement with Vite

## Technologies Used

- **React** 19.0.0
- **Vite** 5.2.0
- **Tailwind CSS** 3.4.19 with @tailwindcss/vite 4.1.18
- **styled-components** 6.1.19
- **ESLint** for linting
- **PostCSS** and **Autoprefixer** for CSS processing

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd reactart
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## Usage

To start the development server:

```bash
npm run dev
```

The app will be available at `http://localhost:5173` (or another port if 5173 is in use).

To build for production:

```bash
npm run build
```

To preview the production build:

```bash
npm run preview
```

To lint the code:

```bash
npm run lint
```

## Project Structure

```
src/
├── components/
│   ├── AuthInputs.jsx
│   ├── Button.jsx
│   ├── Header.jsx
│   ├── Header.module.css
│   └── Input.jsx
├── assets/
│   └── logo.png
├── App.jsx
├── index.css
├── main.jsx
└── index-old.css
public/
├── logo.png
└── vite.svg
```

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run lint` - Run ESLint
- `npm run preview` - Preview production build

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run tests and linting
5. Submit a pull request

## License

This project is private and not licensed for public use.
