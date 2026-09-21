## 2026-09-21 - Game Over Screen A11y
**Learning:** In web-based canvas games, crucial status changes (like game over) often exist as overlaid HTML elements that become visible dynamically. These sudden visual changes are invisible to screen readers unless specifically marked.
**Action:** Always ensure critical game state overlays use `role="alert"` and `aria-live="assertive"` so they are immediately announced when their `display` state changes from `none` to `block`.
