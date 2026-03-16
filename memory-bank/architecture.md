# Project Architecture & Design System

## 1. Technical Stack
- **Engine:** Pure HTML5, Tailwind CSS (via CDN for zero-build demo).
- **Icons:** Lucide Icons (CDN).
- **Fonts:** Geist Sans or Inter (System Sans-Serif).

## 2. Design Language (The "Neon-Noir" Style)
- **Background:** `bg-[#0a0a0a]` (Pure deep black/gray).
- **Surface:** `bg-[#161616]` with `border-[#262626]`.
- **Primary Accent:** `text-blue-500` / `bg-blue-600`.
- **Effect:** Use `backdrop-blur-md` for headers and `shadow-[0_0_15px_rgba(59,130,246,0.2)]` for active elements.
- **Typography:** Tight tracking, uppercase subheaders, and mono-fonts for technical data.

## 3. Structural Rules
- **Componentization:** Even in plain HTML, wrap logical sections in clear comments (e.g., ``).
- **Navigation:** Every new page must have a consistent `<nav>` component.
- **Responsive:** Mobile-first. Use `grid` or `flex` for all layouts.

## 4. AI Behavioral Rules
- NEVER remove the `memory-bank/` folder.
- ALWAYS update `activeContext.md` after a successful build.
- Follow "Atomic Commits" (one feature per PR).