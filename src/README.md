# Source Code (`src`)

This directory contains the client-side application source code for GramUdaan, built with React, TypeScript, and Vite.

## Structure

- `assets/`: Static image assets, SVGs, and brand icons.
- `components/`: Reusable UI components, interactive maps (`IndiaMap`), shell navigation, and role-specific UI widgets.
- `data/`: Curated reference datasets for business categories, calibrated locations, feasibility baselines, and government schemes.
- `engine/`: Core algorithmic models for capital allocation, project cost breakdown, market sizing, and feasibility scoring.
- `hooks/`: Custom React hooks for authentication, animations, responsive layouts, and viewport tracking.
- `i18n/`: Internationalization provider and bilingual translation catalogs (English and Hindi).
- `lib/`: Shared utility helpers, client configurations (Supabase), and onboarding application state management.
- `pages/`: Page components for routing, including auth flows, the 6-step onboarding wizard, analytical dashboards, and planning tools.
- `providers/`: Top-level React context providers, including `SupabaseAuthProvider`.
- `services/`: Service layer integrating Supabase database operations, external government data APIs, geocoding/OpenStreetMap, and AI advisor logic.
- `types/`: TypeScript type definitions and data contracts.
- `main.tsx`: Application entry point setting up routing, error boundaries, and context providers.
