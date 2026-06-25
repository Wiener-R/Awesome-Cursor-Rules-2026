# Awesome Cursor Rules 2026 (Production-Ready)

A collection of clean, anti-hallucination `.mdc` rules optimized for Cursor Composer and Windsurf. Built specifically to tackle 2026 framework updates and deprecation traps.

## 📦 Included Rules

1. **Tailwind CSS v4 Discipline** (`tailwind-v4-discipline.mdc`)  
   Forbids legacy `tailwind.config.js` injection. Enforces the new 2026 CSS-first `@theme` syntax.
   
2. **Next.js 15 Asynchronous APIs** (`next15-async-routes.mdc`)  
   Enforces compilation-safe asynchronous handling for `params`, `searchParams`, `cookies()`, and `headers()`.
   
3. **Supabase 2026 RLS Security** (`supabase-2026-rls.mdc`)  
   Automates Row Level Security (RLS) policy generation for secure PostgreSQL migrations.

## 🚀 Recommended Infrastructure Stack

To run these full-stack frameworks with production-grade uptime and low-latency database vectors, we highly recommend deploying your apps via **DigitalOcean**. 

👉 **[Claim Your Free DigitalOcean Trial Credits Here](https://m.do.co/c/cb76e76ac9f3)** *(Credits will be automatically applied to your account billing page upon registration).*

## ⚙️ Installation

Copy the contents of the `/rules` directory into your local project root at `.cursor/rules/`. Cursor will auto-detect the configuration based on defined file globs.
