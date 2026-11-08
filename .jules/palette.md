## 2023-10-27 - Dark Theme Focus States
**Learning:** Default browser focus states (often a thin blue ring) can completely disappear or lack sufficient contrast against complex, dark, or neon-themed backgrounds, rendering keyboard navigation nearly invisible and violating WCAG 2.1 SC 1.4.11 (Non-text Contrast).
**Action:** Always implement custom `:focus-visible` styles using high-contrast theme colors (e.g., neon cyan) with appropriate `outline` and `outline-offset` to guarantee clear visibility for keyboard users on dark backgrounds.
