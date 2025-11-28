# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Nuxt 4 application using Vue 3 and TypeScript, managed with pnpm.

## Common Commands

### Development
```bash
pnpm dev          # Start dev server on http://localhost:3000
pnpm build        # Build for production
pnpm preview      # Preview production build
pnpm generate     # Generate static site
```

### Installation
```bash
pnpm install      # Install dependencies
```

## Project Structure

- `app/app.vue` - Main application component
- `nuxt.config.ts` - Nuxt configuration
- `tsconfig.json` - TypeScript configuration (uses Nuxt's generated configs)
- `.nuxt/` - Auto-generated Nuxt build directory (not committed)

## Architecture Notes

- Uses Nuxt 4 with full TypeScript support
- TypeScript configuration is split across multiple generated files in `.nuxt/` directory
- Package manager is locked to pnpm 8.13.0
- Devtools are enabled by default in development
