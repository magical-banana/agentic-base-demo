# Project Architecture & Design System

## 1. Technical Stack
- **Engine:** Pure HTML5, Tailwind CSS (via CDN for zero-build demo).
- **Icons:** Lucide Icons (CDN).
- **Fonts:** Space Grotesk (Sans-Serif) for headings, Inter (Sans-Serif) for body.

## 2. Design Language (The "Magical Banana" Style)
- **Background:** `bg-white` / `bg-gray-50`.
- **Primary Accent:** `#FDE047` (Vibrant Yellow).
- **Secondary Accent:** `#A855F7` (Magical Purple).
- **Aesthetic:** High-energy, whimsical, bright, and technical.
- **Effect:** Magical transitions, floating elements, glowing borders, and "peeling" reveals.
- **Typography:** Bold, modern sans-serif for headings (Space Grotesk), clean sans-serif for body.

## 3. Structural Rules
- **Componentization:** Even in plain HTML, wrap logical sections in clear comments (e.g., ``).
- **Navigation:** Every new page must have a consistent `<nav>` component.
- **Responsive:** Mobile-first. Use `grid` or `flex` for all layouts.

## 4. AI Behavioral Rules
- NEVER remove the `memory-bank/` folder.
- ALWAYS update `activeContext.md` after a successful build.
- Follow "Atomic Commits" (one feature per PR).
- When generating SVG or path data, avoid redundant coordinates. Use shorthand commands (H, V, Z) where possible.
- If a code block becomes repetitive or exceeds 50 lines of similar data, use a comment like `` instead of continuing.
- Never output the same coordinate or command sequence more than three times consecutively in a single path string.
- If you notice a specific pattern (like L1200,300L1200,300), you can tell the API to stop immediately if it sees that specific string twice.