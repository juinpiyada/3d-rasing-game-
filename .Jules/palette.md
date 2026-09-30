## 2023-10-24 - Focus Management on Game Over
**Learning:** For dynamic single-page web game overlays, screen reader and keyboard accessibility requires not just semantic HTML (like `role="alertdialog"`) but programmatic focus management. Modals must actively pull focus when instantiated.
**Action:** Always verify keyboard focus states and add a `.focus()` call to primary actions (e.g. "Try Again" button) when a new modal or overlay appears.
