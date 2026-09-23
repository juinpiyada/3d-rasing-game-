## 2026-09-23 - Focus Management on Custom Overlays
**Learning:** Custom game overlays bypass standard browser focus and screen reader announcements. They require explicit focus management and modal roles.
**Action:** Always assign `role="alertdialog"` and explicitly focus the primary action button when an overlay appears.
