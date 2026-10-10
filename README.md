# Adopet

A pet adoption app built with React and Vite, refactored from JavaScript to TypeScript.

## 📖 About

Adopet is a pet adoption web app. The project started as a working React + JavaScript application and was then migrated to TypeScript, adding static typing to components, props, state, and API data.

It was built as my first TypeScript project, following Alura's React learning track.

## 🛠️ Tech Stack

- **React**
- **Vite**
- **TypeScript**
- **json-server**: mock REST API (`server.json`)
- **ESLint**

## 🚀 Getting Started

### Prerequisites

- Node.js 18 or higher
- npm

### Installation

```bash
# Clone the repository
git clone https://github.com/DanielGranato/<repo-name>.git

# Navigate into the project folder
cd <repo-name>

# Install dependencies
npm install
```

### Running locally

The project needs two processes running at the same time: the mock API and the React app.

```bash
# Terminal 1: start the mock API
npx json-server server.json

# Terminal 2: start the React app
npm run dev
```

### Other scripts

| Script | Description |
| --- | --- |
| `npm run build` | Build for production |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint |

## 🔄 Migration to TypeScript

The migration followed these steps:

1. Added TypeScript to the Vite project and renamed files from `.js`/`.jsx` to `.ts`/`.tsx`
2. Typed component props and state
3. Created types and interfaces for the data returned by the API
4. Fixed the type errors reported by the compiler and ESLint

## 🎯 Learning Objectives

This project was built to practice:

- Migrating an existing React project from JavaScript to TypeScript
- Typing props, state, events, and API responses
- Using interfaces and types to model data
- Catching errors at compile time instead of at runtime

## 📄 License

This project is open source and available under the MIT License.
