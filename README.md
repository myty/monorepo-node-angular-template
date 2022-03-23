# Monorepo Template (Node - [Feather.js. Prisma] + Angular)

## Prerequisites

- Node.js (v16)
- Docker

## Getting Started

1. Make sure you have the prerequisites installed.
2. Run: `npm install`
3. Run: `npm run dev`

## Project Structure

This is a monorepo utiizing Docker, Turborepo, Feather.js, Prisma, Angular, and Tailwindcss:

- apps (executable applications)
  - api (Feather.js, Prisma) - depends upon mysql Docker container
  - web (Angular, Tailwindcss)
- packages (shared libraries)
  - config
  - scripts
  - tsconfig
  - ui
