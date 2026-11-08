## 2025-02-12 - Session Storage Caching for API Requests
**Learning:** For static sites without build steps or complex state management, redundant API calls on page reloads (e.g., fetching GitHub profile and repos on every load) can be a significant bottleneck and risk rate limits.
**Action:** Implemented a simple `fetchWithCache` wrapper utilizing `sessionStorage` to persist API responses within the current browsing session, reducing load times on subsequent visits and avoiding unnecessary API requests.
