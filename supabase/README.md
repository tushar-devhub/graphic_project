# Supabase Configuration & Migrations

This directory contains database schema definitions, migrations, and SQL scripts for the GramUdaan Supabase backend.

## Contents

- `production_schema.sql`: Consolidated production database schema establishing:
  - Tables: `profiles`, `reports`, `applications`, and `consultations`.
  - Row Level Security (RLS) policies enforcing role-based access control (entrepreneur, advisor, admin).
  - Database triggers and functions for user profile initialization and role escalation protection.
- `migrations/`:
  - `001_create_gramudaan_schema.sql`: Migration creating core database tables, foreign keys, and indexes.
  - `002_auth_and_roles.sql`: Migration configuring authentication triggers, role checking helper functions, and RLS policies.
