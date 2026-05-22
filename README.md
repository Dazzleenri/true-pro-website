# True Pro Website Core

## Overview
True Pro is an operational management and dispatch dashboard designed specifically for field-service businesses (landscaping, hardscaping, pool/spa services, etc.). This repository contains the front-end code for the True Pro website and functional demo dashboard.

## Tech Stack
- Frontend: React 18
- Build Tool: Vite
- Styling: Tailwind CSS
- Animation: Framer Motion
- Icons: Lucide React

## Brand System Guidelines
Following the recent rebranding, the application uses a strict Navy & Orange theme.

**Target Colors:**
- **Primary Orange:** `#F5A623` (Used for accent buttons, text links, and the True Pro logo)
- **Deep Navy:** `#0F172A` (Used for header, sidebar, primary CTA buttons)
- **Light Backgrounds:** `#F8FAFC` or `#F9FAFB`
- **Slate Text:** `#94A3B8`
- **White:** `#FFFFFF`

**Strict Rules:**
- ❌ No Teal, Green, or Blue accents are permitted.
- ❌ No gradients, glow effects, or unverified stats.
- ✅ All CTAs must use Deep Navy (`#0F172A`) or Orange (`#F5A623`) with white text.

## Form Integration
The "Book an Operational Demo" form is integrated with **FormSubmit**. It posts directly to the administrative contact upon submission without requiring a custom backend.

## Development Commands

**Install Dependencies:**
```bash
npm install
```

**Run Development Server:**
```bash
npm run dev
```

**Build for Production:**
```bash
npm run build
```
