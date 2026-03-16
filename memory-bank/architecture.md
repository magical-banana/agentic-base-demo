# Project Architecture & Design System

## 1. Technical Stack
- **Engine:** Pure HTML5, Tailwind CSS (via CDN for zero-build demo).
- **Icons:** Lucide Icons (CDN).
- **Fonts:** Playfair Display (Serif) for headings, Inter (Sans-Serif) for body.

## 2. Design Language (The "Artisan Cacao" Style)
- **Background:** `bg-[#0f0d0c]` (Deep dark cocoa).
- **Surface:** `bg-[#1a1715]` with `border-[#2d2825]`.
- **Primary Accent:** `text-amber-500` / `bg-amber-600` (Gold/Honey accents).
- **Effect:** Use `backdrop-blur-xl` for headers and sophisticated glass-morphism.
- **Typography:** Elegant serif for headings, clean sans-serif for descriptions.

## 3. Structural Rules
- **Componentization:** Even in plain HTML, wrap logical sections in clear comments (e.g., ``).
- **Navigation:** Every new page must have a consistent `<nav>` component.
- **Responsive:** Mobile-first. Use `grid` or `flex` for all layouts.

## 4. AI Behavioral Rules
- NEVER remove the `memory-bank/` folder.
- ALWAYS update `activeContext.md` after a successful build.
- Follow "Atomic Commits" (one feature per PR).
