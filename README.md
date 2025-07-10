# Cobalt for Vercel Check

This repository contains the Cobalt project configured for deployment on Vercel.

## Project Structure

- `/cobalt` - Main cobalt monorepo
  - `/api` - Backend API
  - `/web` - Frontend SvelteKit application
  - `/packages` - Shared packages
  - `/docs` - Documentation

## Deployment

This project is configured to automatically deploy the web frontend to Vercel. The `vercel.json` file contains all necessary build configurations.

## Local Development

```bash
cd cobalt
pnpm install
pnpm --filter @imput/cobalt-web dev
```

## Build

```bash
cd cobalt
pnpm --filter @imput/cobalt-web build
```
